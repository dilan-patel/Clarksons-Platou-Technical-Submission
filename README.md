# Technical Submission for Clarksons Platou
Author: Dilan Patel  
Date: 09/12/2019

This repository contains the submission for Clarksons Platou front end development test. Out of the 3 technical tests, only the CSS layout test was completed. This task involved creating a responsive web layout for a e-mail messaging type application which can change it's layout. The first layout includes displaying one item per row however for devices with smaller screens (less than or equal to 960px), the layout changes to column-based, so where some items are displayed in the same column.

This task was completed by making the use of a media query which creates a breakpoint at 960px and also using CSS Grids. At first, the task was attempted with by using tables however after implementing the media query, it was difficult to change the layout of the table after the window entered the breakpoint of 960px. To fix this issue, two CSS grids which follow both layouts which the smaller scren layout only being called under the media query so that it only shows when the web page is displayed on smaller devices.

After creating the main responsive feature, the design was implemented by looking at the current website for Clarkson Platou and extracting core elements such as the logo, banner, colour scheme and font styling from their web pages to create consistency in the application's design and company branding. Icons were also added to the item headers to provide readability and an improved user experience. There were also some hover effects added to encourage user intuitiveness. For example, the logo for Clarkson Platou in the header animates and the cursor changes to a pointer instead which suggests the logo is clickable (currently, the logo links to the Clarksons Platou website).

For this task, sections that could be improved upon are the final design of the website. The main focus of this task was to create a responsive layout which was completed successfully but the design could implement accessibility options which could improve the application's user experience. For example, options to increase the text size for readability or option to change to colour scheme to show high contrast for users with visual impairments.


## Instruction for opening test file:

1. Unzip the contents of the clarksons-platou.zip file into a new folder.
2. Open the clarksons-platou.html file using a web browser.
3. Resize the browser window to test the responsive layout by resizing it under 960px.
