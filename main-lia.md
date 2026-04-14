<!--
author: @(Autor.name)
email: @(Autor.mail)
language: @(Projekt.shortlang)
version: @(GetShortGITHash "")
icon: @(Projekt.icon)
date: @(Monat[heute.month].MMMM) @(heute.year)
logo: @Projekt.logo
link: css/jho-lia.css
-->


# @(Projekt.title)

<div style="text-align: center" >
<span style="font-size:x-large; font-weight: bold;">@(Projekt.subtitle)</span>

![](images/@(Projekt.wwwCover))

@(Autor.name)

@(Autor.mail)@(br)

Git: @(GetShortGITHash "")
</div>

@include "main.md"

## Mein ceterum censeo

@include "//home/jho64/Dokumente/AllAboutMe/AboutMeText/ceterum-censeo.md"

