---
context-lang: @(Projekt.contextlang)
title: @(Projekt.title)
subtitle: @(Projekt.subtitle)
cover: @(Projekt.pdfCover)
date: @(Monat[heute.month].MMMM) @(heute.year)
git: @(GetShortGITHash "")
author: @(Autor.name)
---




# @(Projekt.title)

@include "main.md"


## Mein ceterum censeo
@include "//home/jho64/Dokumente/AllAboutMe/AboutMeText/ceterum-censeo.md"
