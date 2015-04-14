FlagMaster
===============================

## Goal
FlagMaster was created as a gift for my now sister-in-law. When she saw a flag at half mast, she wished that she could know WHY the flag was at half mast. She asked me if I could create an iPhone app and, thanks to PhoneGap, here it is

## Features
- Flag data scraped from a third party site using Yahoo! Pipes
- Animated, waiving GIF of American flag that is either at half or full mast depending on whether the actual national flag is currently being observed at half mast
- Select by state to see animated, waiving GIF of your state's flag at either half or full mast
- Explanation for why the national or state flag is at half mast

## Dependencies
- PhoneGap/Cordova
- Yahoo Pipes
- jQuery Mobile
- JS, HTML, CSS

## Caveats
- Yahoo! has removed my account due to inactivity, so I no longer have access to the original pipe that I created to scrape data for the flag status. 
- Due to the above limitation, the app's data source is no longer reliable. The latest year it is reporting is 2014

## Pending Improvements
- Find a cleaner, more reliable source for flag data than site scraping with Yahoo! Pipes
- Improve views with AngularJS
- Refine color scheme
- Save users state flag preference
- Send alerts when flag changes
