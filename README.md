# Assignment 1 - ReactJS app.

Name: Evan Hearne

## Overview.

This repository contains an extended version of the Week 7 Labs from Web App Development 2, a module undertaken in the Computer Science course in third year at South East Technological University (Waterford Campus).

It is extended using additional endpoints, caching, search filters, [add more here later.]

### Features.
[ A bullet-point list of the __new features__ you added to the Movies Fan app (and any modifications to existing features) .]
 
+ Added TV Shows Page with ability to "zoom in" to a specific show via the Details button.
+ Added Regions Page which allows user to see all the regions that TMDB knows about.
+ Added Popular Page with ability to "zoom in" to a specific actor via the Details button.
+ etc
+ etc

## Setup requirements.

[ Outline any non-standard setup steps necessary to run your app locally after cloning the repo.]

```bash
npm install
npm start
```

## API endpoints.

+ TV shows - /tv
+ TV show by id = /tv/:id
+ Watch Provider Regions - /watch/providers/regions
+ Popular actors - /person/popular
+ Popular actors by id - /person/:id

## Routing.

+ /tv - displays all tv shows.
+ /tv/:id - displays a particular tv show.
+ /regions - displays all watch provider regions known by TMDB.
+ /popular - displays all popular actors.
+ /popular/:id - displays a particular actor.

[If relevant, state what aspects of your app are protected (i.e. require authentication) and what is public.]

## Independent learning (If relevant).

Itemize the technologies/techniques you researched independently and adopted in your project, 
i.e. aspects not covered in the lectures/labs. Include the source code filenames that illustrate these 
(we do not require code excerpts) and provide references to the online resources that helped you (articles/blogs).