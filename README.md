# Aura – KI-Musikgenerator

Aura ist eine einzelne HTML-Datei, mit der du über die ACE-Music-API eigene Songs erzeugst. Sie läuft komplett im Browser, ohne Installation und ohne eigenen Server.

**Live-Version:** https://ahuessy.github.io/Aura-Music-Generator/

## Funktionen

- Songs aus einer Stilbeschreibung erzeugen, optional mit eigenen Lyrics und eigenem Titel
- Genre und Stimmung per Klick wählen (je max. 2)
- Dauer automatisch oder manuell in Sekunden, Gesangssprache automatisch erkannt
- Bibliothek mit Suche, Favoriten, Download, Umbenennen und „Neu generieren“
- Playlist aus Favoriten, in der Reihenfolge oder zufällig
- Player mit Lautstärkeregler
- Cover werden im Browser selbst gezeichnet, optional über Fal.ai als KI-Bild

## Benutzung

1. Die Live-Version öffnen.
2. Unter **⚙ API-Einstellungen** deinen eigenen ACE-Music-API-Key eintragen (erhältlich auf [acemusic.ai](https://acemusic.ai)).
3. Stil beschreiben, Genre und Stimmung wählen und auf **Musik generieren** klicken.

Alternativ kannst du `index.html` herunterladen und lokal im Browser öffnen.

## Hinweise

- **Keys:** Dein API-Key wird nur in deinem Browser gespeichert und direkt an den jeweiligen Dienst gesendet. Er ist nicht in dieser Datei enthalten. Trage nie einen Key in den Code ein, bevor du ihn veröffentlichst.
- **Datenschutz:** Songs, Cover und Einstellungen liegen ausschließlich lokal in deinem Browser (localStorage und IndexedDB). Aura hat keine eigenen Server. Zur Musikerzeugung werden Stil und Lyrics an ACE-Music gesendet, bei aktivierter Fal.ai-Option der Stil-Text auch an Fal.ai.
- **Rechte:** Erstelle nur Musik und Texte, die keine Urheberrechte oder Persönlichkeitsrechte Dritter verletzen. Beachte die Nutzungsbedingungen von ACE-Music.
- **Inoffiziell:** Aura ist ein unabhängiges Projekt und steht in keiner Verbindung zu ACE-Step, ACE-Music oder Fal.ai.
