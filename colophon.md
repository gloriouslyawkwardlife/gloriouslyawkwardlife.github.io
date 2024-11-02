---
layout: page
title: Colophon
author: Steven Buehler
date: 2024-11-02
---

This is an explanation of the tools and methods used to keep these pages running like a well-oiled machine. 

## Hosting

The site is hosted with [Github Pages](https://github.io), which uses [Jekyll](https://jekyllrb.com) as the underlying site creation framework.

Jekyll takes files written in HTML, Liquid Markup, and the Markdown to generate static web pages.

## The Daily Log

Source data for the daily logs come from the following:

- [Apple Health](https://apple.com/health) since 1 Nov 2023 for the heart and step data from my Apple Watch Ultra;
- [Foursquare Swarm](https://swarmapp.com) since 31 Dec 2023 for manual location check-ins;
- [Bouncie](https://bouncie.com) since 14 Apr 2023 for vehicle tracking;
- [Overland](https://overland.p3k.com) is a continuous GPS tracking app for iOS that I'm in the process of incorporating. My main concern with it is that continuously having the GPS running is a drain on battery life, and I'm thinking here is that I may instead use a small GPS tracker (like a [Garmin eTrex SE](https://www.garmin.com/en-US/p/835742/pn/010-02734-00) or [eTrex Solar](https://www.garmin.com/en-US/p/869859/pn/010-02782-00)) that has a multiple-day battery life for this purpose.

The daily logs are generated each day using a [Python](https://python.org) script with the following modules:

- `pandas` (and thus indirectly `matplotlib` and `numpy`) to process data;
- `requests` to obtain data from web APIs;
- `zipfile` to handle the `export.zip` file produced by Apple Health;
- `matplotlib` explicitly to customize the charts for presentation and save them to the local repository;
- `staticmaps` to create the map images;
- `os` to invoke some shell commands to push it all to Github.

I plan by the end of 2024 to switch over to the [Wolfram Engine](https://www.wolfram.com/engine) to generate these pages as I like the charts it produces better than what `matplotlib` does and it processes more exotic formats like GeoJSON and GPX a lot more simply; but since Python does the job just fine, too, there's no rush. 