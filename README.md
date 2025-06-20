![Alchemy](./assets/banner.png?raw=true)

[![Latest Version](https://img.shields.io/github/v/release/PetitPrinc3/Alchemy?color=blue)](../../releases/latest)
[![Release date](https://img.shields.io/github/release-date/PetitPrinc3/Alchemy)](../../releases/latest)
[![Latest commit](https://img.shields.io/github/last-commit/PetitPrinc3/Alchemy)](../../commit/master)
[![License](https://img.shields.io/github/license/PetitPrinc3/Deezer?flat)](./LICENSE)

[![Flutter](https://img.shields.io/badge/Flutter-v3.32.2-blue?logo=flutter)](https://flutter.dev/)
[![Dart](https://img.shields.io/badge/Dart-v3.8.1-blue?logo=dart)](https://dart.dev/)
[![Android API](https://img.shields.io/badge/Android%20API-35-green?logo=android)](https://developer.android.com/about/versions/14)
[![Java JDK](https://img.shields.io/badge/Java%20JDK-17-blue?logo=openjdk)](https://openjdk.java.net/projects/jdk/17/)

---

#### :rocket: Alchemy Features:

*   Log in with an official Deezer account;
*   Explore the official Deezer catalog;
*   Play any track and skip freely;
*   Like, save, and add your favorite tracks to your own playlists;
*   Sing along to the songs you love with synchronized lyrics;
*   Download tracks, playlists, and albums for offline listening;
*   Challenge yourself with playlist-based blind tests;
*   Identify the music around you with ACR Cloud song recognition;
*   Export downloaded tracks to local storage;
*   Import your playlists from Spotify;
*   Customize themes, accent colors, and more.

This project originates from [ReFreezer](https://github.com/DJDoubleD/ReFreezer) by @DJDoubleD.

## :hammer_and_wrench: Compile from Source

Get Alchemy running: Follow [these instructions](./HOWTO.md) to compile it yourself.

## :camera_flash: Screenshots

<p align="center">
    <img src="./assets/screenshots/Readme.png" width=80%>
</p>

## :star2: Credits

*   Built upon [ReFreezer](https://github.com/DJDoubleD/ReFreezer) by @DJDoubleD;
*   Lyrics provided by [LRCLIB](https://github.com/tranxuanthang/lrclib) by @tranxuanthang;
*   Design inspired by [Mallari Kishor's Spotify Redesign](https://www.behance.net/gallery/194018249/Spotify-App-Redesign).

## :running: Ongoing Development

*   Moving gateway light API calls to the mobile gateway API  
![](https://geps.dev/progress/80) Login (missing error handling and logout function)  
![](https://geps.dev/progress/95) Artists (missing full discography fetch)  
![](https://geps.dev/progress/0) Albums  
![](https://geps.dev/progress/10) Playlists  
![](https://geps.dev/progress/0) Shows  
![](https://geps.dev/progress/0) Tracks  
![](https://geps.dev/progress/95) Search (missing feature to log recently searched items on click)  

## :building_construction: Upcoming Features

*   Log "clicked" search results in recently searched;
*   Create notification settings;
*   Remove the See All / View More button when it is not required;
*   Implement a profile editing screen;
*   Prefetch lyrics for tracks in the queue;
*   Add lyrics to the downloaded tracks.

## :lady_beetle: Bugs

*   Importing large images for playlist covers is an error and is not handled properly (we need to compress images before upload);
*   The handling of login errors is incomplete;
*   The logout function is broken;
*   Downloads that are stopped and restarted will not be saved in the database and therefore not be available;
*   Skipping tracks on the player screen is not as fluid as it used to be and can be choppy;
*   Some home tiles are not and will not be implemented (Concerts, Did you know, Original videos, ...);
*   [Tell me!](https://github.com/PetitPrinc3/Deezer/issues)

## :balance_scale: Disclaimer & Legal

**Alchemy** was not developed for piracy but for educational and private use.
You are responsible for how you use **Alchemy**.
Using **Alchemy** may be illegal in your country.

**Alchemy** uses both Deezer's public and internal APIs but is not endorsed, certified, or otherwise approved in any way by Deezer.

The Deezer brand and name are the registered trademarks of their respective owner.

**Alchemy** has no partnership, sponsorship, or endorsement with Deezer.

By using **Alchemy,** you do not abide by Deezer's [Terms of Service](https://www.deezer.com/legal/cgu).
