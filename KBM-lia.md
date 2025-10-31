<!--
author: @(Autor.name)
email: @(Autor.mail)
language: @(Projekt.shortlang)
version: @(GetShortGITHash "")
-->

<!-- style = "h1 {color: blue}" -->
# @(Projekt.title)

![](/images/titelbild.png)

@(Autor.name)

@(Autor.mail)@(br)

Git: @(GetShortGITHash "")

## Einleitung

@include "einleitung.md"


## Buchführung und Rechnungswesen

@include "aufgaben-rewe.md"


## Unsere Firma

@include "firma.md"


## Inventur, Inventar, Bilanz

@include "system-technik.md"


## Buchen auf Bestandskonten


## Buchen mit Erfolgskonten


## Die Umsatzsteuer bei Ein- und Verkauf

## Reisekosten/Spesen

@include "reisekosten.md" 

## Mein ceterum censeo

@include "ceterum_censeo.md" 
