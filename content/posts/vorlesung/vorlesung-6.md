---
title: "Vorlesung 6"
date: "2021-11-24"
description: "Verfasst am 28. November 2021"
draft: false
tags: ["Vorlesung"]
summary: "Die Vorlesung ging über das Thema DBpedia. Dabei habe ich gelernt, dass es das Ziel von DBpedia ist, die semi-strukturierten Daten von Wikipedia zu extrahieren und in strukturierte Daten zu überführen, um komplexere Suchanfragen zu realisieren. Für mich neu war, dass Wikipedia bereits aus semi-strukturierten Informationen bzw. Daten besteht und ein Grundgerüst für die Artikel vorgibt. Ebenfalls erstaunlich waren die von Herr Dr. Arndt angegebenen Zahlen/Metriken zu der Wissensdatenbank sowie die eigens von DBpedia erstellte Ontologie. Die von DBpedia benutze Pipeline zur Erstellung dieses Wissens setzt dabei auf neue Technologien und Qualitätssicherungen, die mir ebenfalls aus den praktischen Tätigkeiten als Werksstudent geläufig waren, sodass eine Verknüpfung aus Theorie und Praxis zu erkennen war."
---

{{% quizQuestion %}}
**Quizfrage:** Welchen Vorteil bietet DBpedia gegenüber Wikipedia und wie wird dieser Vorteil erzielt?

**Antwort:** DBpedia ermöglicht es, komplexere Suchanfragen zu beantworten und verknüpfte Aussagen über Wissen zu treffen. Dies ist möglich, indem DBpedia semi-strukturelle Informationen aus Wikipedia extrahiert und in RDF-Triples umwandelt, wodurch eine Verknüpfung von Informationen stattfindet.
{{% /quizQuestion %}}

{{% answeredQuestion %}}
**Frage:** Wie ist die Struktur eines Triples in RDF?

**Antwort:** Ein Triple besteht immer aus Subjekt, Prädikat und Objekt. Diese werden über URIs bzw. IRIs angegeben. Objekte können zudem entweder leere Knoten oder Literale sein.

 

**Frage:** Wie ist der Aufbau von URIs?

**Antwort:** Eine URI besteht aus fünf Bestandteilen: scheme, authority, path, query und fragment. Das häufigste Schema im Web ist dabei http bzw. https. 
{{% /answeredQuestion %}}

Die Vorlesung behandelte das Thema DBpedia. Dabei konnte ich lernen, dass es das Ziel von DBpedia ist, die semi-strukturierten Daten von Wikipedia zu extrahieren und in strukturierte Daten zu transformieren, um komplexere Suchanfragen zu realisieren. Die Erkenntnis, dass Wikipedia bereits aus semi-strukturierten Informationen bzw. Daten besteht und ein Grundgerüst für die Artikel vorgibt, war für mich neu. Ebenfalls erstaunlich waren die von Herr Dr. Arndt angegebenen Zahlen/Metriken zu der Wissensdatenbank sowie die eigens von DBpedia erstellte Ontologie. Die von DBpedia benutze Pipeline zur Erstellung dieses Wissens setzt dabei auf neue Technologien und Qualitätssicherungen, die mir ebenfalls aus den praktischen Tätigkeiten als Werksstudent geläufig waren, sodass eine Verknüpfung aus Theorie und Praxis zu erkennen war.

![DBPedia Pipeline](/lernportfolio/dbpedia-pipeline.png "DBPedia Pipeline")