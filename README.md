# CHPS Website
This repo contains the "Réseau des masters Calcul Haute Performance et Simulation Français" website

## Edition of the website
To edit this website:

* Make a new branch (if you have access to push to this repo) or a new fork.

* Make your changes in your branch/fork.

* Open a pull request.

If you think something on the website should be change, but you're not sure how to do it, please open an issue describing the change you would like to suggest.

## Edition of the website


### Pages
The website is generated from of the content of .md files in the main folder and subfolders (excluding README.md). Markdown and HTML can be included in these files. LaTeX-style maths can be included between \\( and \\) for inline maths; or $$ and $$ for a block of maths.

At the start of each .md file, page setting can be given between two lines containing only ---. For example, index.md starts with:

---
title: Réseau des Masters CHPS
subtitle: fenicsxversion
image: assets/img/logo.jpg
layout: 
permalink: /chps/
---

