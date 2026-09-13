# GitHub-Hinweise

[English](Help.md) · [中文](Help.zh.md) · [Deutsch](Help.de.md)

> **Entwurf:** Deutsche Fassung zur Prüfung durch Mingli29.

## Ein Projekt klonen

Schritt-für-Schritt-Anleitung zum Klonen eines Projekts.

1. Lade die [GitHub CLI](https://cli.github.com/) herunter und authentifiziere dich
2. Öffne das Projekt, das du klonen möchtest
3. Klicke auf den grünen **Code**-Button
4. Wähle Local und GitHub CLI
5. Kopiere den Befehl
6. Öffne Terminal (macOS / Linux) oder CMD / PowerShell (Windows)
7. Klone nicht ins Wurzelverzeichnis. Tippe zuerst `cd documents`
8. Füge den kopierten Befehl ein und drücke Enter
9. Das Repository liegt jetzt in deinem Ordner, in der Regel unter dem Repository-Namen

# Git

## Herunterladen

Git ist ein Open-Source-Versionsverwaltungssystem, das wir für unsere Projekte nutzen.  
Bitte lade [Git](https://git-scm.com/install/mac) herunter, bevor du an Projekten arbeitest.

## Pushen und Pullen

Stelle sicher, dass du Git gemäß [Herunterladen](Help.de.md#herunterladen) installiert hast.

### Pushen

Terminal: `git push`

Wir empfehlen Push über die IDE oder zusätzliche Software. Push und Commit im Terminal brauchen viele Befehle und machen Commit-Details schwerer zu bearbeiten.

### Pullen

Terminal: `git pull`

Branch-spezifisch: `git pull 'remote_name' 'branch_name'`
