#README.MD for Homework 1-Landing Page

## Divya Kalidindi

##Initial Setup
I originally set up the page as per the directions of the assignment, as seen below in the screencap. The basic layout consists of a navigation bar, along with titles, an email address form, "create" button, and a few links at the bottom of the page.

![](http://i.imgur.com/5DvmrcZ.png)

##Features
I mostly followed the example provided in the assignment instructions, and in addition, implemented some of the features described below:

- The navigation bar at the top has a hover feature where the text changes 	from light grey to white. Additionally, when the mouse hovers over the 	navigation bar, the cursor changes to a pointer.
- The teal "create" button also changes to a darker color when the mouse hovers over it.
- The footer buttons change from black to white when hovered over;
- Border radius is implemented for sign-in, as well as input and button fields.

##Finished Page
![]()

## Mobile Version
![]()

## Issues
Some issues I encountered through this lab were:

- I used `position: fixed` for parts of my header and footer. I realized after that this was problematic because as I would scroll, the information on the page would overlap with the header and footer. Thus, I removed this issue in the final version, using flex boxes and also through adjusting the padding.
- I had trouble with white space at the bottom the page, though it never showed up after minimizing the window. I first thought it had something to do with the height and width of the main body, but ended up changing `margin-padding`, which fixed the problem.
