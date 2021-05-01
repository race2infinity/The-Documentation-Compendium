<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="https://i.imgur.com/FxL5qM0.jpg" alt="Bot logo"></a>
</p>

<h2 align="center">Name des Bots</h2>

<div align="center">

  [![Status](https://img.shields.io/badge/status-active-success.svg)]()
  [![Platform](https://img.shields.io/badge/platform-reddit-orange.svg)](https://www.reddit.com/user/Wordbook_Bot)
  [![GitHub Issues](https://img.shields.io/github/issues/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/issues)
  [![GitHub Pull Requests](https://img.shields.io/github/issues-pr/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/pulls)
  [![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center">
    🤖 Ein paar Zeilen, die beschreiben, was der Bot macht.
    <br> 
</p>

## 📝 Inhaltsverzeichnis
+ [Über](#ueber)
+ [Demo / Arbeitsweise](#demo)
+ [Funktionsbeschreibung](#funktionsbeschreibung)
+ [Verwendung](#verwendung)
+ [Einstieg](#einstieg)
+ [Bereitstellen eines eigenen Bots](#bereitstellung)
+ [Erstellt mit](#erstellt_mit)
+ [TODO](../TODO.md)
+ [Mitwirkung](../CONTRIBUTING.md)
+ [Autoren](#autoren)
+ [Danksagung](#danksagung)

## 🧐 Über <a name = "ueber"></a>
Ungefähr 1-2 Absätze, die den Zweck des Bots beschreiben.

## 🎥 Demo / Arbeitsweise <a name = "demo"></a>
![Arbeitsweise](https://media.giphy.com/media/20NLMBm0BkUOwNljwv/giphy.gif)

## 💭 Funktionsbeschreibung <a name = "funktionsbeschreibung"></a>
Der Bot extrahiert zuerst das Wort aus dem Kommentar und ruft dann 
Wortdefinitionen, ein Beispiel und Abstammung aus der Oxford Dictionary-API ab.

Wenn das Wort im Oxford Dictionary nicht vorhanden ist, gibt die Oxford API eine 
404-Antwort zurück, worauf der Bot dann versucht, Ergebnisse aus der Urban 
Dictionary API abzurufen.

Der Bot verwendet die Pushshift-API zum Abrufen von Kommentaren, das PRAW-Modul 
zum Antworten auf Kommentare und Heroku als Server.

Der gesamte Bot ist in Python 3.6 geschrieben.

## 🎈 Verwendung <a name = "verwendung"></a>

Um den Bot zu verwenden folgenden Befehl tippen:
```
!dict word
```
Der erste Teil, als "!dict" **ist nicht** Case sensitiv.

Der Bot gibt Ihnen dann die Definition des Wortes im Oxford Dictionary (oder 
Urban Dictionary; falls das Wort im Oxford Dictionary nicht vorhanden ist) 
als Kommentarantwort.

### Beispiel:

> !dict what is love

**Definition:**

Baby, dont hurt me~
Dont hurt me~ no more.

**Beispiel:**

Dude1: Bruh, what is love? <br>
Dude2: Baby, dont hurt me, dont hurt me- no more! <br>
Dude1: dafuq?

**Quelle:** https://www.urbandictionary.com/define.php?term=what%20is%20love

---

<sup>Beep boop. Ich bin ein Bot. Wenn es Probleme gibt, kontaktiere meinen [Meister](https://www.reddit.com/message/compose/?to=PositivePlayer1&subject=/u/Wordbook_Bot)</sup>

<sup>Willst du einen ähnlichen reddit Bot machen? Probiere: [GitHub](https://github.com/kylelobo/Reddit-Bot)</sup>

## 🏁 Einstieg <a name = "einstieg"></a>
Mit diesen Anweisungen erhalten Sie eine Kopie des Projekts, das zu 
Entwicklungs- und Testzwecken auf Ihrem lokalen Computer ausgeführt werden kann. 
Hinweise zum Bereitstellen des Projekts auf einem Live-System finden Sie unter 
[Bereitstellen eines eigenen Bots](#bereitstellung).

### Voraussetzungen

Welche Dinge werden benötigt um die Software zu installieren und wie wird sie 
installiert?

```
Hier Beispiele geben
```

### Installation

Eine Schritt für Schritt Anleitung die zeigt, wie die Entwicklungsumgebung zum 
Laufen gebracht wird.

Beschreibe den Schritt

```
Gib ein Beispiel
```

Und wiederhole

```
bis zur Fertigstellung.
```

Zum Schluss noch ein Beispiel, wie einige Daten aus dem System geholt werden 
oder für eine kleine Demo verwendet werden.

## 🚀 Bereitstellen eines eigenen Bots <a name = "bereitstellung"></a>
Ein Beispielprojekt zur Bereitstellung Ihres Bots finden Sie in meiner eigenen 
Konfiguration:

+ **Heroku**: https://github.com/kylelobo/Reddit-Bot#deploying_the_bot

## ⛏️ Erstellt mit <a name = "erstellt_mit"></a>
+ [PRAW](https://praw.readthedocs.io/en/latest/) - Python Reddit API Wrapper
+ [Heroku](https://www.heroku.com/) - SaaS hosting platform

## ✍️ Autoren <a name = "autoren"></a>
+ [@kylelobo](https://github.com/kylelobo) - Idee & Erste Version

Siehe auch die Liste der [Mitwirkenden](https://github.com/kylelobo/The-Documentation-Compendium/contributors), die an diesem Projekt teilgenommen haben.

## 🎉 Danksagung <a name = "danksagung"></a>
+ Hut ab vor Jedem, dessen Code verwendet wurde
+ Inspiration
+ Verweise
