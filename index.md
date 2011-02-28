---
layout: default
title: Arlukin Articles
---

[Welcome]({{ site.url }})<br/><abbr>14 Jan 2011</abbr>
======================================================

This page will be the main page for the Open Archive Network project.

Imagine yourself one folder on your computer, in which you can store any file
you like. No mater how big or small, important or not important. You will
know that the file can be retrived again later. No matter what happens your
accidentely delete it, your hard drive will crash, somebody breaks in to your
home and steal all your electronics or maybe the whole place will burn down to the ground.

That folder is stored on the Open Archive Network.

## The phases

* Analyze - starting 2011-05-01
* Specification - starting 2011-08-01
* Proof of concept - starting 2011-09-01

## Contribute to this webpage.

Here is some code to help you check out this website make changes and push it back.</p>
    #!/usr/bin/sh
    git config --global user.name "Daniel Lindh"
    git config --global user.email daniel@cybercow.se

    cd ~
    mkdir documents
    git clone https://arlukin@github.com/oan/documents.git
    vi index.html
    git add index.html
    git commit -m"Added news"
    git push origin


