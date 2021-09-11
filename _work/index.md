---
layout: default
title: My Work
nav_order: 1
---

# Valuable Work Experiences
### I'm honored to have chances to work in the following companies/schools and to improve my skills with my wise collegues.

## Gerzz Interative
  worked as a `Back End Developer` from Feb 2021 to Aug 2021. I contributed to two projects

  1. Project Halo - Online Murder Mystery Application <span style="color:black">where I</span>
  {: .text-purple-100 }

  * <span style="font-family:Menlo;">Implement a message queue service to accepting requests for each script play gaming room so that each player in the room is able to search clue, enter sub chatroom asynchronously.</span>
  * <span style="font-family:Menlo;">Implement strategy to allow for reconnecting to the original gaming room after disconnection by routinely updating essential data in the gaming room to database.</span>
  * <span style="font-family:Menlo;">Design configurations for each drama script in order to store static information such as clues, scenes, background music in database.</span>
  * <span style="font-family:Menlo;">Use Redis to record each user s online status by updating redis key each time a user sends a request to server.</span>
  * <span style="font-family:Menlo;">Use MySql and Redis to record each users following and followed list by inserting follow data to MySql and adding following/followed user id to ZSET. Implement method to automatically retreive the following, followed list from MySql and Redis back to server each time when a user login to the application.</span>

  2. Project Juhuipin - WeChat Mini Application <span style="color:black">where I</span>
  {: .text-purple-100 }

  * <span style="font-family:Menlo;">Build an algorithm for recommending activities for each user on plaza. The recommendation system is based on the frequency of user clicking into different categorical events.</span>
  * <span style="font-family:Menlo;">Add notification feature to the mini app so that (1) when one user asks to join in an activity, the event holder is able to be notified, and respond to the application (2) when holder replied to the application, the user is able to be notified for the result of the application (3) when event is beginning in less than one hour, all event participants get notified (4) when event cancels, all event participants get notified.</span>
  * <span style="font-family:Menlo;">Add local cache system for storing all activies, user information and plaza information in order to reduce the stress of MySQL. Plan to transfer local cache to redis so that the information stored in local cache stay in case of server crashes.</span>
        

## Tencent
  worked as a `Back End Developer` from Dec 2020 to Feb 2021. My main job was to
  * <span style="font-family:Menlo;">Use Local Network Interface API for a service.</span>
  * <span style="font-family:Menlo;">Implement strategy certain material corresponded REDIS data value to be cleared(both hash key value and string key value) when service switch from pre environment to formal environment.</span>
  * <span style="font-family:Menlo;">Implement local cache feature in various downstream services in order to store commonly accessed data in local cache instead of frequently fetching data from Redis. Improve efficiency and prevent docker from failing due to large flow of data. Modify local cache configuration in formal environment based on docker memory.</span>
  * <span style="font-family:Menlo;">Transfer several publish services from old RPC framework to new RPC framework for better efficiency, add related unit tests. Monitor log outputs and keep track of error messages. Locate error and Edit paragraphs in service that might cause service to panic.</span>
  * <span style="font-family:Menlo;">Improve code styles: Enable some constant variables (e.g. REDIS server address, REDIS server password) to read values from configuration to prevent hijacking private information and to incorporate configuration modifications; Categorize different types of error and print categorized error codes on logs to improve debug effectiveness.</span>

## Shanghai Jiao Tong University
  worked as a `research assistant` from May 2019 to July 2019.
  * <span style="font-family:Menlo;">Read through research papers, Interpreted facial recognition calculations based on these researches, and Trained sample faces in face dataset using support vector machine.</span>
