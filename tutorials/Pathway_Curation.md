# Pathway Curation
# Curate pathways in WikiPathways
===============================================================================
## November 26, 2019
---------------------------------------------------------------------------------------------------

In this part, we want to show you how to curate the pathways in WikiPathways. This will also show you some of the common mistakes people 
make when creating their own pathways.

If you want to become a pathway curator, you can follow the [quality assurance protocol](https://wikipathways.github.io/academy/qaprotocol.html) in the WikiPathways Academy


### Unconnected lines

One major curation task is to connect lines that are not correctly connected in the wikipathways database. This allows the connections between 
nodes to be characterized in a machine readable way.

The list of pathways with unconnected lines can be found [here](https://docs.google.com/spreadsheets/d/1HE8Rj6yEbhcMokph25Bmk3utpZ2ezCAZxRsFgEwtHVU/edit?usp=sharing). The page contains 3 sheets, each with pathways from a different species.
Sheet one is homo sapiens, sheet two is Mus musculus, and sheet 3 is Rattus norvegicus.

**Step 1: Choose the pathway you will work on**. Make sure you put your name in the "working on" column so you don't end up working on 
the same pathway as someone else.

**Step 2: Find the pathway in Wikipathways** by clicking on the link in the spreasdsheet. Each pathway has an associated identifier that is
starts with WP followed by numbers. Copy the identifier (example WP485).

**Step 3: Open the pathway in PathVisio** by clicking *Plugins* - *Wikipathways* - *Search* in the menu bar.

![Figure 1](https://github.com/LaurenDupuis/EJP-RD_Helis_Academy/blob/master/tutorials/figures/Picture1.png)

This will open a popup window. Click on the Pathway Search tab and search for the pathway identifier.

![Figure 2](https://github.com/LaurenDupuis/EJP-RD_Helis_Academy/blob/master/tutorials/figures/Picture2.png)

Double click on the pathway to open it. 

**Step 4: Find the unconnected lines** by pressing Ctrl + L. The place that a line is unconnected will be highlighted with a green node.

![Figure 3](https://github.com/LaurenDupuis/EJP-RD_Helis_Academy/blob/master/tutorials/figures/Picture2and1.png)

Connect the line to the node.

**Step 5: Upload the curated verion to WikiPathways** by clicking *Plugins* - *Wikipathways* - *Update* in the menu bar. A popup box 
will appear where you need to describe the changes you have made. Fill in "Connected unconnected lines" and click Update.

![Figure 4](https://github.com/LaurenDupuis/EJP-RD_Helis_Academy/blob/master/tutorials/figures/Picture3.png)

Then you will have to fill in your WikiPathways account information, and the pathway will be updated with your contribution. Don't forget 
to update the spreadsheet by clicking the check box marking the pathway as done.


### Other curation tasks

We focus on unconnected lines, but if you want to work on other tasks, the list of tags for pathways that need curation can be found [here](https://www.wikipathways.org/index.php/Special:CurationTags)


