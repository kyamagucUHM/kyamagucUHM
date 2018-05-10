---
layout: project
type: project
image: images/UHSwapShop_Landing_Mockup.png
title: UH Swap Shop Final Project
permalink: projects/UHSwapshop
# All dates must be YYYY-MM-DD format!
date: 2018-5-4
labels:
  - Final Project
  - Java Script
  - Meteor React UI
summary: Final Project using Meteor React
---
  Final Project for ICS 314 to design and implement functionality for a basic website.  This project was 
filled with many challenges and provided a solid learning experience.  Areas of learning include collaborative
design and problem solving, using GitHub to work together in shared code to implement functions that lead to 
the desired goal.  The project the group chose was to design and setup a Craigslist like exchange for UH students
in order to provide an experience where students can exchange unwanted items for cash or work out trades of item
for another.  No member of the group had much experience with website ascetics, so a simple design and layout based
on the UH colors was selected by the group.  We discussed the neccessary features needed for the exchange of items
and what would be required for users to engage with each other.
  Major challenges included the implementation of User profiles that contained the needed information.  The profiles
were implemented using Meteor Collections and layered over the Meter User profile system. The biggest issue was soft
linking the custom profile system to the Meteor User system used to login into the site.  Then linking the custom
profile system to the item listings and having them call back to each other when needed.  This feature was never fully
fleshed out due to a lack of indepth knowledge of how to manipulate Meteor Subscribe functions and collections in the
specific way we needed to.  Late in development a workable implementation was prototyped but was unable to be finalized
due to some errors in execution.
  Other features left out of the final release were a messaging system, item search, want listing and item offer
indicators. Some of these features were beyond the scope of the group abilities, others were left out due to lack of time
caused by relative inexperience with Meteor React that left us hammering out issues with implementing other parts of the
site.  Looking back on this, I feel that structuring the development differently and focusing more on narrowing the scope
of some areas of the project would have allowed us to get more features in and make sure every needed feature was included.
Primary example of this would be restrict item listing to a general list first, implement the profiles and profile linking
fully along with the individual item card pages then expand into categories and custom searches.  Another option would be
to restructure the Item List into a page of the Item Collection as Cards instead of a table and eschew the need to have 
separate links to each item in the table.
  Overall I feel that the project was a great experience in learning collaborative development environments and a way to
foster a group work mindset.  Despite failing to meet all goals that we as a group set, the failures incurred provided
an opportunity to learn things not to do when planning a project of this size and how not to underestimate the requirements.

