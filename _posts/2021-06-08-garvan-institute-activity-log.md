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
| 09/06/2021 | 7 | Was able to split polyprotein 1ab into polyprotein a and polyprotein b. Also was able to scale the proteins to fit window size, and seperate the ones that do not fit into new lines. |
