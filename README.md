<p align="center">
 <a href="https://himdek.com/Better-Kicker-for-Plasma/"><h1 align="center">Better Kicker</h1></a>
 <p align="center">An improved fork of KDE Plasma's Kicker Application Menu</p>
</p>

<p class="buttons" align="center">
 <a href="https://github.com/HimDek/Better-Kicker-for-Plasma/issues"><img alt="GitHub issues" src="https://img.shields.io/github/issues/HimDek/Better-Kicker-for-Plasma?style=flat-square"></a>
 <a href="https://github.com/HimDek/Better-Kicker-for-Plasma/pulls"><img alt="GitHub pull requests" src="https://img.shields.io/github/issues-pr/himdek/Better-Kicker-for-Plasma?style=flat-square"></a>
 <a href="https://github.com/HimDek/Better-Kicker-for-Plasma/"><img src="https://img.shields.io/badge/GitHub-View%20sourcecode-blue?style=flat-square&logo=github&color=blueviolet" /></a>
 <a href="https://github.com/HimDek/Better-Kicker-for-Plasma/blob/master/LICENSE.md"><img alt="GitHub license" src="https://img.shields.io/github/license/HimDek/Better-Kicker-for-Plasma?style=flat-square"></a>
 <a href="https://github.com/HimDek/Better-Kicker-for-Plasma/actions/workflows/pages/pages-build-deployment/"><img src="https://img.shields.io/github/deployments/HimDek/Better-Kicker-for-Plasma/github-pages?label=WebPage%20build%20status&logo=InternetExplorer&style=flat-square" /></a>
 <a href="https://github.com/HimDek/Better-Kicker-for-Plasma/network"><img alt="GitHub forks" src="https://img.shields.io/github/forks/HimDek/Better-Kicker-for-Plasma?style=flat-square"></a>
 <a href="https://github.com/HimDek/Better-Kicker-for-Plasma/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/HimDek/Better-Kicker-for-Plasma?style=flat-square"></a>
</p>

<p class="buttons" align="center">
  <a href="#gallery"><img src="https://img.shields.io/badge/View%20Screenshots-blueviolet?style=for-the-badge" /></a>
  <a href="https://himdek.com/?tab=donate"><img src="https://img.shields.io/badge/Donate-Support%20me-green?style=for-the-badge&logo=Razorpay" /></a> 
  <a href="https://himdek.com/Better-Kicker-for-Plasma/"><img class="invisible" src="https://img.shields.io/badge/himdek.com-View%20in%20Website-blue?style=for-the-badge&logo=Internet-Explorer&color=blue" /></a>
  <a href="#prerequisites"><img src="https://img.shields.io/badge/Install-green?style=for-the-badge" /></a>
</p>

<p class="buttons" align="center">
  <a href="#powerful-plasma-search"><img src="https://img.shields.io/badge/Powerful%20Plasma%20Search-blue?style=for-the-badge" /></a>
  <a href="#changes-made-over-default-kickoff"><img src="https://img.shields.io/badge/Differenciation%20from%20Kickoff-orange?style=for-the-badge" /></a>
</p>

This is an improved fork of KDE Plasma's Kicker Application Menu which is a launcher based on cascading popup menus. The design is simplified while improving search features and customizability.

## Powerful Plasma Search

The search bar uses `Plasma Search`, which is the same search provider used in Krunner, Kickoff Application Launcher and the Overview effect which supports powerful search plugins and providers.

###### **NOTE:** The initial codebase was copied from Kicker which can be found in `/usr/share/plasma/plasmoids/org.kde.plasma.kicker/`, on every Linux system that has KDE Plasma installed.

## Prerequisites:

* Linux based Operating System
* [KDE Plasma Desktop Environment](https://kde.org/plasma-desktop/)
* [Plasma-Framework Package](https://github.com/KDE/plasma-framework)

<p align=>Make sure you have plasma-framework package installed by execute the following command:</p>
<p align=>
  <pre>sudo apt install plasma-framework</pre>
</p>

<h1 align="center">Get it from</h1>

<p align="center">
  <a href="https://www.pling.com/p/1897850"><img height="50px" src="https://img.shields.io/badge/Pling%20Store-informational?style=for-the-badge&color=orange" /></a>
  <a href="https://store.kde.org/p/1897850"><img height="50px" src="https://img.shields.io/badge/KDE%20Store-informational?style=for-the-badge&logo=KDE" /></a>
  <a href="https://www.opendesktop.org/p/1897850"><img height="50px" src="https://img.shields.io/badge/openDesktop-informational?style=for-the-badge&color=blueviolet" /></a>
</p>

<p align="center">Install it directly from any of the above mentioned sources</p>

<p align="center">or</p>

<p align="center">If you have download the file, extract it, open a terminal in the directory containing the `metadata.desktop` file and execute the following command:</p>

<p align="center">
  <pre>kpackagetool5 -t Plasma/Applet --install</pre>
</p>

## Changes made over default Kicker:

* Disabled the favorite applications shown in the side bar because the original Kicker Application Menu of KDE Plasma looks broken if too many Applications are added to favourites. Favorite applications are now shown in a dedicated menu category
* Shows all the session and power buttons viz Lock, Logout, Switch User, Sleep, Restart and Shut Down
* Ability to enable or disable the `Favorites` menu category.
* Powerfull and improved search: The search bar now supports all the features of Plasma Search or Krunner
* Unified design: Removed unnecessary separators. Every component now shares the same background and looks cleaner

<h1 id="gallery" align="center">Gallery</h1>

<p align="center">
<img height="400px" src="assets/20220905_172656_Nodic_Run_Command.png" align="center"/>
<img height="400px" src="assets/20220905_172709_Breeze_Calculator.png" align="center"/>
<img height="400px" src="assets/20220905_172717_Sweet_Web_Search.png" align="center"/>
<br /><br />
<img height="300px" src="assets/20220905_172732_Nordic.png" align="center"/>
<img height="300px" src="assets/20220905_172756_Breeze_Favorites.png" align="center"/>
<img height="300px" src="assets/20220905_172801_Sweet_Icons.png" align="center"/>
</p>
