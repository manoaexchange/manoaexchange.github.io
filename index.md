## Table of Contents
* [Overview](#overview)
* [Goals](#goals)
* [Developer's Guide](#developers-guide)
* [User Guide](#user-guide)
* [Development Progress](#development-progress)
  * [Milestone 1](#milestone-1)
  * [Milestone 2](#milestone-2)
 * [Community Feedback](#community-feedback)
* [Contributors](#contributors)

---

## Overview
<img src="images/home.PNG">

Manoa Exchange is a Meteor Application that allows the UH Manoa community to sell their unwanted dormitory and/or apartment appliances. This makes it easy for students, faculty, and staff alike to post and find potential products, along with setting up a meeting on campus to exchange goods. 

---

## Goals 

* Connect the UH Manoa community 
* Buy/Sell goods
* Provide an easy to use interface to facilitate transfer of goods between people

---

## Developers Guide 

1. Install [meteor.](https://www.meteor.com/install)
2. Download [Manoa Exchange.](https://github.com/manoaexchange/manoaexchange)
3. CD into app/ directory and install libraries.
`meteor npm install`
4. Run application.
`meteor npm run start`
5. Open Application on [http://localhost:3000/.](http://localhost:3000/)

---

## Startup

Manoa Exchange is a UH community tool.  Registration will be required for access to all features of the application.  To register, click sign in at the top right of the page, and in the dropdown menu, click sign up.  You will be taken to the sign up page to quickly create an account, after creation you will have full access to the features the application.  You will be able to search for a multitude of items being offered by members of the UH community, or list items of your own.

---

## User Guide

### Landing Page
The first page you will see is the introduction page, letting you know the capabilities of the application.
<img src="images/landing.PNG">

### Register an Account 
In order to access the features of ManoaExchange, you need to register
<img src="images/register.PNG">

### Sign-in Page
If you have an account, click the login icon on the top right of the website.
<img src="images/signin.PNG">

### Home Page
Logging in will redirect you to the home page which will allow you further access to features of the application.
<img src="images/home.PNG">

### Profile Page
One feature is creating a profile page to see a summary of currently listed items for sale. You may also view other users profile pages.
<img src="images/profile1.PNG">
<img src="images/profile2.PNG">

### Edit Profile Page
Need to make changes to your profile? Edit as you need.
<img src="images/editprofile.PNG">

### Create an Item
List an item you no longer want up for sale.
<img src="images/createitem.PNG">

### Edit an Item
Edit the information of your item.
<img src="images/edititem.PNG">

### Categories
Don't know what you want? Search by category
<img src="images/categories.PNG">

### Search By Categories
List of all items in your category.
<img src="images/categorylist.PNG">

### Report a user
Unfortunately you may run into inappropriate behavior from other users on this site. Click on the report button to notify an admin of the issue.
<img src="images/report.PNG">

### Admin Page
Admins view reports submitted by users and from their judgement, may or may not delete the item or user said reports is on. 
<img src="images/admin.PNG">

---

## Development Progress

This section shows our progress in creating the application. 

### Milestone 1

**Status: Complete**

**Versions 1-6**

**Date: 3/31/19-4/11/19**

Start creating mockup pages for a select few pages. We first started coding in a React application. Once we had our mockup pages created, we transferred it over to the Meteor application. Along with the mockup pages, links toward over half the pages work, but are not implemented yet. 

Pages Worked On:
* Landing page
* Sign in/Sign up pages
* User Home page
* Profile page
* Message Page
* Report page

As of now, the landing page, user home, profile, message and report pages are only mockup pages. Sign in/sign up allows a user to sign in but does not redirect to correct page. And the landing page has both the navigation bar for new users and signed it users. The navigation bar will be fixed once user only functions is imnplemented, and is there only to show what it looks like for new users. 

See [Milestone 1 Project Board](https://github.com/manoaexchange/manoaexchange/projects/1) for more details.

### Milestone 2

**Status: Complete**

**Versions 7-20**

**Date: 4/12/19 - 4/25/19**

**Goals:** Finish Mockup for remaining pages and implement functions of Milestone 1 pages along with a few extra functions. 

**Summary of completed tasks:** 
* Collections for items, messages and reports
* List of owned items 
* Edit the item
* Search by category 
* Messages system

See [Milestone 2 Project Board](https://github.com/manoaexchange/manoaexchange/projects/2) for more details.'

### Milestone 3

**Status: Incomplete**

**Versions 21-**

**Date 4/26/19 -**

**Goals:**
Finish all remaining issues and create a consistent theme across the site. Clean up any leftover and unused files.

**Summary of completed tasks:** 

See [Milestone 3 Project Board](https://github.com/manoaexchange/manoaexchange/projects/3)
for more details

---

## Community Feedback
*"Posting items was useful and easy. However some areas did not work such as messages"* 

Undergrad Senior computer science major

*"The listing items was easy to use. The ui design needs work"* 

Undergrad Junior Computer Science major

## Contributors

This was a joint project created by [Shawn Anthony,](https://shawn-anthony.github.io/ "Shawn Anthony") [Christopher Na,](https://chrisn3.github.io/ "Christopher Na") and [Katherine Piniol.](https://piniolk.github.io/ "Katherine Piniol")

[Top of Page](#table-of-contents)


