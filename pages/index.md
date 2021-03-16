---
layout: page
title: OpenFOAM?
permalink: /
---

# OpenFOAM trouble shooting

install ~ running ~ error

<img src="assets/img/1.Ref_hysing_microBubbles.gif" alt="gif1"  width="10%" height="10%"/>
<img src="assets/img/2.airD_hysing_microBubbles_noPhaseTransfer.gif" alt="gif2"  width="10%" height="10%"/>
<img src="assets/img/3.airD_hysing_microBubbles_noPhaseTransfer_fine.gif" alt="gif3"  width="10%" height="10%"/>
<img src="assets/img/4.airD_hysing_microBubbles_phaseTransfer.gif" alt="gif4"  width="10%" height="10%"/>
<img src="assets/img/5.airD_hysing_microBubbles_phaseTransfer_fine.gif" alt="gif5"  width="10%" height="10%"/>

## Purpose

GitHub pages uses Jekyll natively, so when I make documentation, I typically
look for Jekyll templates. Why? Using Jekyll means that I can use markdown,
and allow for users to easily contribute, and build automatically just by
way of pushing to a master branch (or general GitHub pages).
I found Docsy, a beautiful Hugo template, but it requires hugo with GoLang
which doesn't render natively on GitHub pages. For this reason, I've spent
some time creating a custom Jekyll template that is (almost) as beautiful,
and includes all the features that I might want.

## Features

What are these features? You should see the {% include doc.html name="Getting Started" path="getting-started" %}
guide for a complete summary. Briefly:

 - *User interaction* including consistent permalinks, links to ask questions via GitHub issues, and edit the file on GitHub directly.
 - *Search* across posts, documentation, and other site pages, with an ability to exclude from search.
 - *External Search* meaning an ability to link any page tag to trigger an external search.
 - *Documentation* A documentation collection that was easy to organize on the filesystem, render with nested headings for the user, and refer to in markdown.
 - *Pages* A separate folder for more traditional pages (e.g, about).
 - *Navigation*: Control over the main navigation on the left of the page, and automatic generation of table of contents for each page on the right.
 - *News* A posts feed for news and updates, along with an archive (organized by year).
 - *Templates* or specifically, "includes" that make it easy to create an alert, documentation link, or other content.
 - *Continuous Integration* recipes to preview the site


For features, getting started with development, see the {% include doc.html name="Getting Started" path="getting-started" %} page. Would you like to request a feature or contribute?
[Open an issue]({{ site.repo }}/issues)
