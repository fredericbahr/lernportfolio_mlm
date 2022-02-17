---
title: "Vorlesung 7"
date: "2021-12-01"
description: "Verfasst am 02. Dezember 2021"
draft: false
tags: ["Vorlesung"]
summary: In dieser Vorlesung haben wir uns mit dem Tool OpenRefine beschäftigt, um Daten zu bearbeiten, zu bereinigen oder zu entfernen. Überrascht hat mich die doch komplizierte Installation von OpenRefine unter Windows, wo eine ZIP-Datei gedownloadet und entpackt werden muss und die RDF-Extension im richtigen Ordner, mit richtigem Namen abzulegen war. Hier wäre eine Installation per Wizard oder per CLI wünschenswert. Leider hat dieser Teil auch den Großteil der Vorlesung in Anspruch genommen, sodass wenig Zeit für die praktische Auseinandersetzung mit dem Tool an sich blieb. Jedoch konnte ich das Potenzial von OpenRefine erkennen und war überrascht von der Anzahl an built-in Methoden, um die Daten zu bearbeiten und zu bereinigen. Auch die Verwendung des RDF-Plugins um die Tabelle (Daten) in RDF-Triple umzuwandeln, war hilfreich und verdeutlichte die Einsatzmöglichkeiten dieses Tools in der Praxis. Der mangelnden Zeit schulden will/müsste ich mich aber noch intensiver mit diesem Tool beschäftigen."
---

{{% quizQuestion %}}
**Quizfrage:** Wozu kann OpenRefine einerseits verwendet werden?

**Antwort:** OpenRefine mit der RDF-Extension kann dafür verwendet werden Datensätze einzulesen, zu bearbeiten und zu bereinigen. Zusätzlich können dann die Daten per Mapping in RDF Triples übersetzt werden und so einen RDF-Graphen erstellt werden.
{{% /quizQuestion %}}

{{% answeredQuestion %}}
**Frage:** Was ist DBpedia und warum nutzt man DBpedia?

**Antwort:** DBPedia extrahiert Daten aus Wikipedia und stellt diese strukturiert als Linked Data zur Verfügung. Dadurch werden diese Informationen einerseits maschinell abrufbar, andererseits können komplexe Suchanfragen gestellt werden.

 

**Frage:** Nennen Sie eine wesentliche Gemeinsamkeit und einen Unterschied von DBpedia
und Wikidata.

**Antwort:** 
Gemeinsamkeiten:
- Versuchen Informationen aus Wikipedia strukturiert zu speichern
- Abfrage per SPARQL


Unterschiede:
- Aufbau der strukturierten Informationen (RDF vs. JSON, XML, SQL)
- Repräsentation von Fakten (Triple vs. Statements und Claim)
- DBpedia extrahiert Daten/Informationen
- Wikidata erhält Informationen über Eingabe durch Autor
{{% /answeredQuestion %}}

Im Rahmen der Vorlesung haben wir uns mit dem Tool OpenRefine beschäftigt, um Daten zu bearbeiten, zu bereinigen oder zu entfernen. Verwunderlich war die komplizierte Installation von OpenRefine unter Windows, bei der eine ZIP-Datei gedownloadet und entpackt werden muss. Ebenfalls erforderlich war es die RDF-Extension im richtigen Ordner, mit korrektem Namen abzulegen. Hier wäre eine Installation per Wizard oder per CLI wünschenswert. Aufgrund dieser organisatorischen Hürde blieb innerhalb der Vorlesung wenig Zeit für die praktische Auseinandersetzung mit dem Tool. Jedoch konnte ich das Potenzial von OpenRefine erkennen und war überrascht von der Anzahl an built-in Methoden, um Daten zu bearbeiten und zu bereinigen. Auch die Verwendung des RDF-Plugins um Tabellen (Daten) in RDF-Triple umzuwandeln, war hilfreich und verdeutlichte die Einsatzmöglichkeiten dieses Tools in der Praxis. Der mangelnden Zeit schulden will/müsste ich mich aber noch intensiver mit diesem Tool beschäftigen.

Nachtrag: Die weitere Auseinandersetzung hat sich als praktisch erwiesen, da so im Vortrag der essenca GmbH einige Parallelen zwischen OpenRefine und essencas Extraktion von Daten und Generierung von RDF Triples erwiesen hat.

