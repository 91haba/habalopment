+++
author = "haba"
title = "VIPER Architecture Pattern With SwiftUI & Combine"
date = "2021-08-09"
tags = [
    "swiftui",
    "combine",
    "ios",
]
categories = [
    "tutorial",
    "architecture",
    "designpattern"
]
series = ["Themes Guide"]
aliases = ["migrate-from-jekyl"]
+++


## Headings

[Raywenderlich Getting Started with the VIPER Architecture Pattern](https://www.raywenderlich.com/8440907-getting-started-with-the-viper-architecture-pattern) tutorial 번역 및 요약 정리

## Getting Started
- The ContentView will launch the app’s other views as you build them.
- There are some helper views in the Functional Views group: one for wrapping the MapKit map view, a special “split image” view, which is used by the TripListCell. You’ll be adding these to the screen in a little bit.
- In the Entities group, you’ll see the classes related to the data model. Trip and Waypoint will serve later as the Entities of the VIPER architecture. As such, they just hold data and don’t include any functional logic.
- In the Data Sources group, there are the helper functions for saving or loading data.
- Peek ahead if you like in the WaypointModule group. This has a VIPER implementation of the Waypoint editing screen. It’s included with the starter so you can complete the app by the end of this tutorial.

