# Roommate Finder

## Table of Contents

1. [Overview](#Overview)
2. [Product Spec](#Product-Spec)
3. [Wireframes](#Wireframes)
4. [Schema](#Schema)

## Overview

### Description

Roommate Finder serves as an accessible medium for UCSD students looking for roommates living on-campus since the UCSD on-campus housing system can make it hard for people to room with friends from different colleges

### App Evaluation

   - **Category:** Social Networking
   - **Mobile:** Mobile let's you bring the app on the go and get notifications whenever you get new matches! The one downfall of restricting this to a web-only app would be for this very reason.
   - **Story:** People will be able to match with people who have similar living habits and live in the same college!
   - **Market:** This is uniquely for UCSD students who plan on living on campus, although this can definitely be expanded to the entire UCSD population (beyond on-campus housing) with future updates!
   - **Habit:** People will be constantly meeting and interacting with new potential roommates through this app!
   - **Scope:** The barebones first V1 would include user profile creation and being able to see the collection of other users who have high-decent compatibility! I hope to be able to implement features for liking profiles and seeing the profiles that matched with you during this V1 as well. V2 would be implementing chat functionality, updating user profiles/deleting profiles, profile/password recovery, blocking/ignoring certain profiles. V3 would include implementing "group" profiles where multiple profiles are presented under the same group profile, safety/reporting options... in general this app idea has a lot of potential to grow and there are many great inspirations out there (i.e. hinge, tinder, etc.)

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* Create a user profile with UCSD google email
* Feed view displaying users who have decent-high compatibility with current user
* Display view for showing users who have sent likes
* Allow users to respond to & send out likes
* Push notifications when user receives a handful of unchecked likes
* Users can log in and out

**Optional Nice-to-have Stories**

* Updating user profile
* Deleting user profile
* Chat functionality
* Profile/password recovery
* Blocking/ignoring profiles
* Implementing "group" profiles
* Safety/reporting system

### 2. Screen Archetypes

**Login Screen**
* Users can log in

**Registration Screen**
* Create a user profile with UCSD google email

**Scouting View**
* Feed view displaying users who have decent-high compatibility with current user
* Users can send likes

**Likes View**
* Users can respond to likes they've received

**Tab Bar**
* Users can log out and access the 2 main views, scouting & likes view

**Device**
* Users will receive notifications when they received a handful of unchecked likes

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Explore Feed
* Likes Page
* Log Out

**Flow Navigation** (Screen to Screen)

- Login Screen
* => Explore Feed
* => Registration Screen
- Registration Screen
* => Home Feed
- Home Feed
* => None
- Likes Screen
* => None

## Wireframes

[Add picture of your hand sketched wireframes in this section]
<img src="YOUR_WIREFRAME_IMAGE_URL" width=600>

### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

## Schema 

[This section will be completed in Unit 9]

### Models

[Add table of models]

### Networking

- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]
