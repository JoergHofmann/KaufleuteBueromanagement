<!--
author: @(Autor.name)
email: @(Autor.mail)
language: @(Projekt.shortlang)
version: @(GetShortGITHash "")
icon: @(Projekt.icon)
date: @(Monat[heute.month].MMMM) @(heute.year)
-->

<section style="text-align:center">)


![](images/@(Projekt.wwwCover))

@(Autor.name)

@(Autor.mail)@(br)

Git: @(GetShortGITHash "")
</section>

@include "main.md"

## Mein ceterum censeo

@include "//home/jho64/Dokumente/AllAboutMe/AboutMeText/ceterum-censeo.md"

