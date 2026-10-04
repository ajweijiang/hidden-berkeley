# Hidden Berkeley: HW2 starter

Create your own public website from this starter, then use a Jupyter notebook to edit the data it displays.

**Start here:** on the [HW2 template repository](https://github.com/macss-berkeley/hw2-hidden-berkeley-template), choose **Use this template → Create a new repository**. Name your copy `hidden-berkeley` and make it public. Clone your copy with GitHub Desktop and open its folder in VS Code. Follow [hw2_hidden_berkeley.ipynb](hw2_hidden_berkeley.ipynb).

## What is in this repository?

| File | What it does |
| --- | --- |
| `hw2_hidden_berkeley.ipynb` | Your instructions, data edits, and submission evidence. |
| `docs/_data/locations.csv` | The resource data. The notebook edits this file; the website reads it. |
| `docs/index.md` | The page heading, introduction, and supplied loop that displays the CSV rows. |
| `docs/_config.yml` and `docs/_layouts/default.html` | Supplied website settings and layout. |

GitHub Pages builds the website from `main` and `/docs`. After you push a changed CSV, GitHub rebuilds the page using the new data. Jupyter only edits and saves the data; it does not build the website. The `_data` folder name is required by the website builder.

## Purpose and sources

This guide is for new community members at Berkeley to discover resources at UC Berkeley. The first eight resources were supplied by the template but I added the UC Berkeley Career Center after looking on Berkeley's Center for Support and Intervention for Campus & Community Resources. The link to Berkeley's Center for Support and Intervention is here: https://csi.berkeley.edu/. Under their Campus & Community Resources subpage (https://csi.berkeley.edu/campus-community-resources/), I found the Career Center under "Student Engagement". You can look at the Career Center's website here: https://career.berkeley.edu/.


## Website checks

Here is the live website link: https://ajweijiang.github.io/hidden-berkeley/
From the template, I updated the Morrison Library entry to have a slightly more verbose "Access note". I also added the UC Berkeley Career Center as the 9th resource. I learned about the Career Center through Berkeley's Center for Support and Intervention and the Career Center's website. I checked their About Us page (https://career.berkeley.edu/about-us/) to see which Berkeley community members could access their resources. The displayed values match my CSV and the official links open the intended pages. The only thing to note is that the "BAMPFA Film Library" and Study Center and the "Berkely Art Museum and Pacific Film Archive" link to the same Official Source.
