# Plan for Pickem

Deadline Sep 1, 2022

## Core Features

* Sign up/leave.
* Join group, leave group, invite to group, group admin.
* Choose picks per week.
* See all players’ picks.
* See standings and winner of the week.
* Review prior weeks’ data.
* Watch stats of games live.
* Use an ESPN data source at first, but make it swappable.
* Predictive rankings.
* Support players joining/leaving the group in a week (including disqualifications).

## Tenets

* Open source.
* Regular commits.
* Multiplatform wherever possible.
* Professional quality code.
* Well-tested.

## Priorities

* Ktor backend with oauth support.
* Web admin frontend.
* KMP models & biz.
* Picks domain-specific interface for the live data source; ESPN provider implementation.
* Android client.
* Compose interface, ideally in jetbrains to allow a web version.

## Stretch Goals

* Presence in Google Play.
* Clean up your website.

## Planning

Planning must include traceable and trackable progress.

By the end of March, have a reasonable schedule laid out.

Start with discovery of the unknowns. Identify the things that are really unknown, and prototype them early.

Then prototype system integration. Make sure you’ve got an end-to-end flea circus.

The unknowns should be known by the end of May, depending on what you’ve identified.

## Unknowns

* How to build an oauth user system.
* Backing database to support users.
* Administrative web interface to manage users.
* Jetbrains Compose, particularly Web interface.
* ESPN data source. Abstract it so you could switch to an NFL API if needed.
