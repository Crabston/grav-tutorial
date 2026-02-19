---
title: Remote Support mit RustDesk
slug: remote-support-mit-rustdesk
sitemap:
  changefreq: yearly
  priority: 0.5
  lastmod: 17-02-2026
date: 17-02-2026
taxonomy:
  category: Support
  tag: [ Anleitung, Support, RustDesk ]
header_image_file: hero.webp
hero_image: hero.webp
hero_classes: 'text-light overlay-dark parallax'
---

!!! In dieser Anleitung zeigen wir auf, wie unsere Kunden mit dem Remote Support Tool RustDesk schnell und unkompliziert Hilfe von uns erhalten können. 

===

RustDesk ist eine benutzerfreundliche Fernwartungssoftware, die es ermöglicht, den Bildschirm eines entfernten Computers zu sehen und zu steuern. So können wir von überall aus auf einem Computer arbeiten, um Probleme zu beheben oder andere Aufgaben zu erledigen, als wären wir direkt davor.

## RustDesk Funktionen
RustDesk ist eine leistungsstarke Open Source Fernwartungssoftware für jegliche Betriebssysteme mit mehr als 30 Millionen Downloads und über 10 Millionen aktiven Nutzern weltweit. Sie bietet eine Vielzahl von Funktionen, darunter:
- **Einfache Verbindung**: Verbinde dich mit einem entfernten Computer durch die Eingabe einer eindeutigen ID und eines Passworts.
- **Sicherheitsfunktionen**: RustDesk verwendet Ende-zu-Ende-Verschlüsselung, um die Sicherheit der Verbindung zu gewährleisten.
- **Plattformübergreifend**: RustDesk ist für Windows, macOS, Linux, Android und iOS verfügbar, sodass du von jedem Gerät aus auf einen entfernten Computer zugreifen kannst.
- **Dateiübertragung**: Übertrage Dateien zwischen deinem lokalen Computer und dem entfernten Computer, um Dokumente, Bilder oder andere Dateien auszutauschen.
- **Chat-Funktion**: Kommuniziere mit dem Benutzer des entfernten Computers über die integrierte Chat-Funktion, um Anweisungen zu geben oder Fragen zu klären.
- **Sitzungsaufzeichnung**: RustDesk ermöglicht die Aufzeichnung von Fernwartungssitzungen, um sie später anzusehen oder zu dokumentieren.

## RustDesk Nutzen
Wie profitieren unsere Kunden von RustDesk?

Unsere Kunden profitieren von RustDesk, da es ihnen ermöglicht, schnell und unkompliziert Hilfe von uns zu erhalten, ohne dass ein Techniker vor Ort sein muss. Dies spart Zeit und Kosten, da wir Probleme aus der Ferne beheben können, anstatt einen Vor-Ort-Termin zu vereinbaren. 

### Installation
Die Installation von RustDesk ist einfach und unkompliziert. Lade die neueste Version von RustDesk auf der [RustDesk Download Seite](https://github.com/rustdesk/rustdesk/releases/latest) oder über folgende Link herunter:
- [Windows](https://s.crabston.ch/support-rustdesk?device=windows)
- [macOS](https://s.crabston.ch/support-rustdesk?device=macos)
- [Android](https://s.crabston.ch/support-rustdesk?device=android)
- [iOS](https://s.crabston.ch/support-rustdesk?device=ios)

Öffne die heruntergeladene Datei und folge den Anweisungen auf dem Bildschirm, um RustDesk zu installieren. Nachdem RustDesk installiert ist, starte die Anwendung, falls sie nicht automatisch gestartet wird.

### Benutzeroberfläche
Die RustDesk Benutzeroberfläche sieht wie folgt aus:
![RustDesk Benutzeroberfläche](rustdesk-1.png?lightbox)

1. Statusleiste: Zeigt den Verbindungsstatus an.
2. ID: Mit dieser eindeutigen ID können andere Benutzer eine Verbindung zu deinem Computer herstellen.
3. Einmalpasswort: Ein temporäres Passwort, das für die Verbindung verwendet wird. Es ändert sich nach jeder Sitzung und muss jedes Mal neu mitgeteilt werden.
4. Verbindungsfeld: Mit diesem Feld kannst du die ID eines entfernten Computers eingeben, um eine Verbindung herzustellen.
5. Menü-Schaltfläche (⋮): Hier findest du weitere Optionen und Einstellungen für RustDesk.

### Verbindung herstellen
Um eine Verbindung zu einem entfernten Computer herzustellen, benötigst du die ID und das Einmalpasswort des entfernten Computers. Gib die ID des entfernten Computers in das Verbindungsfeld ein und klicke auf "Verbinden". Du wirst dann aufgefordert, das Einmalpasswort einzugeben. Sobald du das Passwort eingegeben hast, wird die Verbindung hergestellt und du kannst den Bildschirm des entfernten Computers sehen und steuern.

Nachdem du die ID eingegeben hast, wird auf dem entfernten Computer zusätzlich eine Benachrichtigung angezeigt, dass jemand versucht, eine Verbindung herzustellen. Der Benutzer des entfernten Computers kann die Verbindung akzeptieren oder ablehnen. Wenn er die Verbindung akzeptiert, muss das Einmalpasswort nicht eingegeben werden, da die Verbindung bereits autorisiert ist.

## RustDesk bei Crabston
Wir bei Crabston nutzen RustDesk, um unseren Kunden schnellen und unkomplizierten Support zu bieten. Dazu haben wir einen eigenen RustDesk Server eingerichtet, der es uns ermöglicht, Verbindungen zu unseren Kunden herzustellen. Durch unseren eigenen Server können wir die Sicherheit und Zuverlässigkeit der Verbindungen gewährleisten und unseren Kunden eine bessere Erfahrung bieten. 

Um unseren RustDesk Server zu nutzen, muss jedoch auf dem Computer des Kunden unser Server konfiguriert werden:
1. Kopiere folgender Konfigurationstext in die Zwischenablage:
```
9JSPrxWMFhEWvNmZ0dGdyMTQ2hnWtFWOUhHWyQEWoNETlNlbzdDUC1GejtSeGJiOikXZrJCLiIiOikGchJCLiIiOikXYsVmciwiIoNmLu9GdzJWYyNmL0J3bwBXdz5yciJGaiojI0N3boJye
```
2. Öffne RustDesk und klicke auf die Menü-Schaltfläche (⋮) neben der ID
3. Navigiere in den Einstellungen zu "Netzwerk > ID / Relay Server"
4. Füge die kopierte Konfiguration über den "Importieren" Knopf ein, und verifiziere, dass im ID Server Feld folgender Text erscheint: `hbbs.support.crabston.ch` ![RustDesk Server Konfiguration](rustdesk-2.png?lightbox)
5. Klicke auf "OK", um die Einstellungen zu speichern und verifiziere auf der Startseite in der Statusleiste, dass die Verbindung zum Server erfolgreich hergestellt wurde.

## RustDesk für jeden
RustDesk kann über die öffentlichen Server kostenlos und von jedem genutzt werden. So kannst du RustDesk auch für deine eigenen Zwecke verwenden, um Freunden oder Familienmitgliedern bei Computerproblemen zu helfen, oder um von unterwegs auf deinen eigenen Computer zuzugreifen. 