
# WEB102 Prework - **Nautilus Analytics**

  

Submitted by: **Josh Park**

  

**Nautilus Analytics** is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

  

Time spent: **6-7** hours spent in total

  

## Required Features

  

The following **required** functionality is completed:

  

* [x] The introduction section explains the background of the company and how many games remain unfunded.
* [x] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [x] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
* [x] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

  

The following **optional features** are implemented:

  

* [x] Navigation bar with links to sections, e.g., Stats, Our Games and logo-link to top of the page
* [x] Search bar features:
  * [x] Matching search result (can be a substring) to any of the game's names
  * [x] Can either *click search icon* or press *enter* to have searched results displayed 
  * [x] Click on ***x*** will clear previous results and restore to default, e.g., 11 games showing  

  

## Video Walkthrough

  

Here's a walkthrough of implemented features:

<img src="walkthrough_web102.gif" title="Video Walkthrough" width="100%" alt="Video Walkthrough" />

GIF created with [Kap](https://getkap.co/) for macOS

  

## Notes

  

* CSS styling the navigation bar, e.g., using text-decoration: none not on the ```<ul>``` itself but the nested links
* Using pseudo-selectors correctly for adding extra touch, like ```:hover```
* I was testing the function **```filterUnfundedOnly```** after I wrote out the block of code that would filter ```GAMES_JSON``` and display only seven games.  However, all eleven games showed up.  This happened because an EventListener was not added to the 'Show Unfunded Only' button to invoke ```filterUnfundedOnly()```.
* Changing an ```id``` to ```class``` name, and the repercussions not just styling-wise, but in javascript. Especially if you're using ```getElementById``` but will now have to adapt and use ```querySelector``` instead. 

  

## License
Copyright [2026] [Josh Park]

Licensed under the Apache License, Version 2.0 (the "License");

you may not use this file except in compliance with the License.

You may obtain a copy of the License at

  

http://www.apache.org/licenses/LICENSE-2.0

  

Unless required by applicable law or agreed to in writing, software

distributed under the License is distributed on an "AS IS" BASIS,

WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.

See the License for the specific language governing permissions and

limitations under the License.
