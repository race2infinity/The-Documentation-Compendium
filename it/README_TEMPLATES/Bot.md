<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="https://i.imgur.com/FxL5qM0.jpg" alt="Bot logo"></a>
</p>

<h3 align="center">Nome del Bot</h3>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![Platform](https://img.shields.io/badge/platform-reddit-orange.svg)](https://www.reddit.com/user/Wordbook_Bot)
[![GitHub Issues](https://img.shields.io/github/issues/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/pulls)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center"> 🤖 Qualche riga per descrivere le funzionalità del tuo bot.
    <br> 
</p>

## 📝 Indice

- [Descrizione](#about)
- [Demo / Funzionamento](#demo)
- [Come Funziona](#working)
- [Utilizzo](#usage)
- [Come Iniziare](#getting_started)
- [Deployare il tuo bot](#deployment)
- [Costruito Con](#built_using)
- [TODO](../TODO.md)
- [Contribuire](../CONTRIBUTING.md)
- [Autori](#authors)
- [Riconoscimenti](#acknowledgement)

## 🧐 Descrizione <a name = "about"></a>

Scrivi circa 1-2 paragrafi descrivendo lo scopo del tuo bot.

## 🎥 Demo / Funzionamento <a name = "demo"></a>

![Funzionamento](https://media.giphy.com/media/20NLMBm0BkUOwNljwv/giphy.gif)

## 💭 Come Funziona <a name = "working"></a>

Il bot per prima cosa estrae la parola dal commento e poi ottiene le definizioni, parte del discorso, esempio e fonte dalla API di Oxford Dictionary.

Se la parola non esiste in Oxford Dictionary, l'API Oxford restituisce una risposta 404, per cui il bot prova ad ottenere risulati dall'API di Urban Dictionary.

Il bot usa Pushshift API per ottenere commenti, PRAW module per rispondere ai commenti e Heroku come server.

Per intero il bot è scritto in Python 3.6

## 🎈 Utilizzo <a name = "usage"></a>

Per usare il bot, scrivi:

```
!dict word
```

La prima parte, i.e. "!dict" **non** tiene conto del maiuscolo o minuscolo.

Il bot quindi ti darò la definizione secondo Oxford Dictionary (o Urban Dictionary; se la parola non esiste in Oxford Dictionary) come risposta.

### Esempio:

> !dict what is love

**Definition:**

Baby, dont hurt me~
Dont hurt me~ no more.

**Example:**

Dude1: Bruh, what is love?
Dude2: Baby, dont hurt me, dont hurt me- no more!
Dude1: dafuq?

**Source:** https://www.urbandictionary.com/define.php?term=what%20is%20love

---

<sup>Beep boop. I am a bot. If there are any issues, contact my [Master](https://www.reddit.com/message/compose/?to=PositivePlayer1&subject=/u/Wordbook_Bot)</sup>

<sup>Want to make a similar reddit bot? Check out: [GitHub](https://github.com/kylelobo/Reddit-Bot)</sup>

## 🏁 Come Iniziare <a name = "getting_started"></a>

Queste istruzioni ti daranno una copia del progetto funzionante sul tuo computer locale per scopi di sviluppo e testing. Vedi [deployment](#deployment) per istruzioni su come deployare il progetto.

### Prerequisiti

Di cosa hai bisogno per installare il software e come installarle.

```
Dai esempi
```

### Installazione

Una serie di esempi passo a passo che ti dicono come avviare un ambiente di sviluppo.

Indica qual è il passo

```
Dai l'esempio
```

E ripeti

```
Fino alla fine
```

Chiudi con un esempio su come ottenere dei dati dal sistema o su come usarlo per una piccola demo.

## 🚀 Deployare il tuo bot <a name = "deployment"></a>

Per vedere un esempio di progetto su come deployare il tuo bot, vedi la mia configurazione:

- **Heroku**: https://github.com/kylelobo/Reddit-Bot#deploying_the_bot

## ⛏️ Costruito con <a name = "tech_stack"></a>

- [PRAW](https://praw.readthedocs.io/en/latest/) - Python Reddit API Wrapper
- [Heroku](https://www.heroku.com/) - SaaS hosting platform

## ✍️ Autori <a name = "authors"></a>

- [@kylelobo](https://github.com/kylelobo) - Idea & Lavoro iniziare

Vedi anche la lista di [contributori](https://github.com/kylelobo/The-Documentation-Compendium/contributors)
che hanno partecipato a questo progetto.

## 🎉 Riconoscimenti <a name = "acknowledgments"></a>

- Cenno a tutti quelli il cui codice è stato utilizzato
- Ispirazione
- Riferimenti
