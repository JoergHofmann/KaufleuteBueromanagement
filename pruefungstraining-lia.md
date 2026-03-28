<!--
author: @(Autor.name)
email: @(Autor.mail)
language: @(Projekt.shortlang)
version: @(GetShortGITHash "")
icon: @(Projekt.icon)
date: @(Monat[heute.month].MMMM) @(heute.year)
logo: @Projekt.logo
-->

# @(Projekt.ptTitle)

<div style="text-align: center" >
@(Projekt.ptSubtitle)

![](images/@(Projekt.wwwCover))

@(Autor.name)

@(Autor.mail)@(br)

Git: @(GetShortGITHash "")
</div>



## Das Wichtigste in Kürze

@include "pt-zusammenfassung.md"

## Mein ceterum censeo

@include "//home/jho64/Dokumente/AllAboutMe/AboutMeText/ceterum-censeo.md"

