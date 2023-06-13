---
title: Depremsel App
author: Enes Ozturk
date: 2023-04-14 01:30:00 +0000
categories: [Blogging, Projects]
tags: [projects]
---

# DepremselApp
- [project link](https://github.com/nsozturk/DepremselApp "depremselApp")
## Overview

Depremsel App is an iOS application that displays a list of recent earthquakes in a table view. Each earthquake is colored according to its magnitude, with stronger earthquakes appearing in reddish colors. The app also allows users to click on a cell to view more details about a particular earthquake.

## Installation

1. Clone or download the repository to your local machine.
2. Open the <span style="color:red ">*DepremselApp.xcodeproj*</span> file in Xcode.
3. Select a simulator or a physical device to run the app on.
4. Click the "Run" button in Xcode to build and run the app.

## Screenshots

![Desktop View](https://github.com/nsozturk/DepremselApp/raw/main/assets/depremsellapp-1.png){: width="234" height="506" }{: .normal }
![Desktop View](https://github.com/nsozturk/DepremselApp/raw/main/assets/depremsellapp-2.png){: width="234" height="506" }{: .normal }




## Features

- View a list of recent earthquakes in a table view
- Sort the earthquakes by date or magnitude.
- Color-code the earthquakes by magnitude
- Click on a cell to view more details about a particular earthquake
- View earthquake on a map

## Todo

[ ] Add a notification when the "Fetch" button is pressed, if there are earthquakes with a spesific magnitude.

[ ] Display earthquake on a map which has turkey's all faults drawin.

## Credits

The earthquake data is sourced from the Kandilli observatory and earthquake research institute (KOERI)

The app also uses the Kandilli Rasathanesi API (https://github.com/orhanayd/kandilli-rasathanesi-api) to retrieve earthquake data in Turkey. We would like to thank Orhan AYDIN (https://github.com/orhanayd) for creating and maintaining this API.

We would also like to thank Mehmet Ali Pekcan (https://github.com/mapelse) for creating and sharing the Fay Hatları project (https://github.com/mapelse/fayHatlari), which helped us to include all of the fault lines in Turkey in the app.