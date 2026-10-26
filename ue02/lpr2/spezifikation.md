# Spezifikation des Terminplaners — Gliederung und Beispiele

Mitgearbeitet haben (GitHub-Benutzernamen, auch bei Einzelarbeit): @leroghost

<!-- Je Abschnitt Ihrer Gliederung eine Überschrift (## für Abschnitte, ###
     für Unterabschnitte) und darunter ein Beispiel aus dem Terminplaner,
     d.h. so, wie Sie den Sachverhalt in diesem Abschnitt festhalten würden.
     Die beiden Überschriften unten sind lediglich Platzhalter. -->

## 1. Systemübersicht und Ziele
Der Terminplaner soll Studierenden der THM das Buchen von Sprechstunden erleichtern und Sekretariate entlasten.

- **Beispiel:** Das System bietet eine webbasierte Buchungsseite, auf der Studierende nach Login über das Hochschulkonto freie Zeitslots von Lehrenden einsehen und mit wenigen Klicks buchen können.

## 2. Funktionale Anforderungen (Funktionen)
Hier wird definiert, welche konkreten Aktionen das System unterstützen muss.

- **Beispiel:** Nach erfolgreicher Buchung erzeugt das System automatisch eine `iCal`-Datei für den Kalender der beteiligten Personen und versendet eine Bestätigungs-E-Mail.

## 3. Schnittstellen (Interfaces)
Beschreibung, wie das System mit externen Systemen oder KI-Komponenten kommuniziert.

- **Beispiel:** Das System stellt eine REST-API bereit, über die autorisierte KI-Agenten im Auftrag von Studierenden freie Termine abfragen und verbindlich buchen können.

## 4. Benutzeroberfläche und Bedienung (UI/UX)
Wie die Masken für den Nutzer aufgebaut sein sollen.

- **Beispiel:** Die Buchungsseite zeigt eine kalendarische Wochenansicht, in der verfügbare Termine grün und bereits belegte Termine grau dargestellt werden.