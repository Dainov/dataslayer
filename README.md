dataslayer
==========

A Chrome extension to enhance Google Tag Manager dataLayer debugging.

Installation
------------
To use the unpacked source version, enable Developer mode in the [Chrome extensions page](chrome://extensions/) and *Load unpacked extension* from the checked-out **src** folder.

The latest official version will always be available at the [Chrome Web Store](https://chrome.google.com/webstore/detail/dataslayer/ikbablmmjldhamhcldjjigniffkkjgpo).

Use
---
A new panel will appear in Developer Tools titled **dataslayer**, containing a page group and URL for each pageload in the tab, with each dataLayer.push appearing in a subgroup. To collapse and expand page groups, simply click the URL associated with each page.