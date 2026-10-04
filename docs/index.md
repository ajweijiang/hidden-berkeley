---
layout: default
title: Hidden Berkeley
---

# Not-So-Secret Berkeley Spots!

Are you new to Berkeley and want to get exploring? Here's a list for a new bear to find community, space, and services at Berkeley. You can take a look at the official pages for more information on access details!

<!-- Edit the heading and introduction above. The supplied loop below displays each row of the CSV. -->
{% for resource in site.data.locations %}

### {{ resource.name | escape }}

**Category:** {{ resource.category | escape }}  
**Area:** {{ resource.area | escape }}  
**Access note:** {{ resource.access_note | escape }}  
<a href="{{ resource.source_url | escape }}">Official source</a>

{% endfor %}

---

The entries come from this project's CSV. Confirm current details using the official links.
