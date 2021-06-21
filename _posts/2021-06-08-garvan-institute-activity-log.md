---
layout: post
title: Garvan Institute Activity Log
---

| Date        | Hours | Activity  |
| :--------- :|:----:| ---------------- |
| 1/06/2021  | 7 | Recieved my access badge, and started to look into the code for the project. |
| 2/06/2021  | 7 | Tried to figure out the API calls. Played around with the D3 library, drawing simple shapes. Called backend information including getting sequence lengths from the database in order to draw arrows. |
| 04/06/2021 | 6 | Running into some async issues in JavaScript. Need to have a look at promises. Managed to render the arrow shapes, and have them render one after another as required. |
| 07/06/2021 | 7 | Figured out the async javascript call, and resized triangles when sequence length is very small. Started on some javascript events. On mouse over for tooltip pop ups. Made it more reactive with highlighting. Will discuss with mentor tormorrow about creating some new database calls to get required information for ordering the proteome. |
| 08/06/2021 | 2 | Added a redirect on click for each of the arrows, using the primary accession of each protein. Opens in a new tab in Aquaria. |
| 08/06/2021 | 5 | Set up the node.js backend server. Created a new API call that can be accessed from the front end to the server code. The ordering sequence of the proteins are now done. Next need to figure out a way to cut the overlaps of proteins, and also to create the splits into thirds for the UI. |
| 09/06/2021 | 7 | Was able to split polyprotein 1ab into polyprotein a and polyprotein b. Also was able to scale the proteins to fit window size, and seperate the ones that do not fit into new lines. Started work on an axis |
| 11/06/2021 | 7 | Added a ruler to the larger proteins, and smaller labels to sub 300 amino acid proteins. Also added text labels to all proteins that fit it. Next would be to look into fetching synonyms to label the smaller proteins that cannot fit a full name |
| 15/06/2021 | 7 | Got some feedback about the ruler, and did some modifications with how the ticks are marked. And figured out an algorithm to split the three groups into roughly equal lengths rather than as close as possible to the overall average 1/3 of the length. |
| 16/06/2021 | 7 | Made the ruler for residue number continuous for all fragments of polyproteins. Got the protein synonyms from database and used different names for any preferred names that are too long to fit onto the arrows. The script now works for SARS and MERS. Also added images of the proteins and started finding matching structures. The bottom element for matching structures of each non-dark protein is now in place. |
| 18/06/2021 | 6 | Adjusted the page to remove unused components from prototype. Modified the structure to have each of the 1/3 displayed in a separate element. Started looking at D3 transitions and animations. Thinking about how to generate and size images, and how to make an expandable graph. |
| 21/06/2021 | 6 | Now gets images from the image server if there was no preferred image saved. Created the expand and collapse buttons and functionality. The rows can now be expanded and collapsed individually. Added transition. |
