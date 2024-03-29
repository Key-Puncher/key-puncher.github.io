---
layout: post
title: Garvan Institute Activity Log
---

### Garvan Institude 2 Month Placement Activity Log
Includes the date, hours, and quick summary of work completed.

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
| 21/06/2021 | 6 | Now gets images from the image server if there was no preferred image saved. Created the expand and collapse buttons and functionality. The rows can now be expanded and collapsed individually. Added transition for the expanding and collapsing, opacity and other visuals. Spoke with my supervisor about the next steps, building calls for the fragmentation of NSP proteins. Next step would be to refactor and render them. |
| 22/06/2021 | 7 | Did some significant refactoring of the code to have better style. Started working on the NSP protein fragments, encountering some issues. Taking some time to plan out the approach as it is quite complex. Managed to render them in order. Pushed the changes to the server as well. |
| 23/06/2021 | 6 | Refactored the code a bit more. Completed the expand and collapse functionality, and it now changes view to support browsers with different aspect ratios like mobile. Now renders a loading page while in the process of rendering d3 components. Also had a discussion with my supervisor about using Vue bindings to control state. Now investigating now to do that. |
| 25/06/2021 | 7 | Looked into refactoring the Vue component, but didn't manage to get it working. Had the mid-session review with the supervisor. Plan is to start working on the dark regions next week. There is now a lockdown order and Garvan is in the affected area, so I'll be working from home starting next week. |
| 28/06/2021 | 7 | Created a database call for getting the non-dark regions of proteins, and refactored the other calls removing hardcoded urls. Was able to render the non-dark regions, but there are some bugs for the polyprotein. |
| 29/06/2021 | 6 | I have managed to render the non-dark regions with rectangles, however I decided to completely refactor the code and attempt to create the non-dark regions using the supported gradient fill in the arrows themselves. There's some issues with blurring, but I'm trying to find a way around it so that there is no colour blending for the gradients. By refactoring the rectangles and triangles into a single shape, it removes a lot of unneeded complexity in the code. The polyproteins are still broken. |
| 30/06/2021 | 6 | There is a bug in chrome where the dividers are blurred. It works fine in Firefox and Safari. Seems to be an issue with the way web-kit renders gradients. Not sure how to fix it yet, posted a question on stack overflow. |
| 02/07/2021 | 5 | Stackoverflow didn't get any good responses sadly. Tested it a bit more and reported the bug to chrome bug tracker. Will likely have to implement a workaround specifically for chrome. |
| 05/07/2021 | 6 | Continued to investigate the chrome bug. Came up with several different methods of resolving it. Found a few others who had experienced similiar issues. Decided ultimately to split up larger gradients instead of implementing another solution. Managed to get that working quite nicely. Also spoke with the professor about a possible extension to the internship, in order to continue the work. |
| 06/07/2021 | 6 | Got the NSP proteins to work. Next steps are to add a saturation change to collapsed elements and add the starting and ending padding arrows. Also modify the expand buttons to be arrows. |
| 12/07/2021 | 6 | Was able to get the expand buttons to work, added some reactivity. Now using the accordion layout and the expand buttons are arrows. The collapsed elements and rulers were adjusted to have less white spaces. Arrows now change direction depending on which element is currently expanded. |
| 13/07/2021 | 6 | More fiddling with design issues. |
| 16/07/2021 | 6 | Code refactoring |
| 20/07/2021 | 5 | Added the padding proteins in the margins, allowing the different segments to be continous |
| 21/07/2021 | 6 | Added the ruler to the top of padding proteins. Discussed with supervisor about the end of the internship and possible contract extensions. |
