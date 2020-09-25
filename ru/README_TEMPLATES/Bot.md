<p align="center"><a href="" rel="noopener">  </a><img width="200px" height="200px" src="https://i.imgur.com/FxL5qM0.jpg" alt="Логотип бота"></p>

<h3 align="center">Имя бота</h3>

<div align="center">
</div>

[]()![Статус](https://img.shields.io/badge/status-active-success.svg)




---

<p align="center">🤖 Несколько строк, описывающих, что делает ваш бот.<br></p>

## 📝 Содержание

- [About](#about)
- [Demo / Working](#demo)
- [Как это устроено](#working)
- [Применение](#usage)
- [Getting Started](#getting_started)
- [Развертывание собственного бота](#deployment)
- [Построен с использованием](#built_using)
- [TODO](../TODO.md)
- [Contributing](../CONTRIBUTING.md)
- [Авторы](#authors)
- [Благодарности](#acknowledgement)

## 🧐 About <a name="about"></a>

Напишите примерно 1-2 абзаца, описывающих назначение вашего бота.

## 🎥 Демо / Работа<a name="demo"></a>

![За работой](https://media.giphy.com/media/20NLMBm0BkUOwNljwv/giphy.gif)

## 💭 Как это работает<a name="working"></a>

Бот сначала извлекает слово из комментария, а затем извлекает определения слова, часть речи, пример и источник из Oxford Dictionary API.

If the word does not exist in the Oxford Dictionary, the Oxford API then returns a 404 response upon which the bot then tries to fetch results form the Urban Dictionary API.

Бот использует Pushshift API для получения комментариев, модуль PRAW для ответа на комментарии и Heroku в качестве сервера.

Весь бот написан на Python 3.6.

## 🎈 Использование<a name="usage"></a>

Чтобы использовать бот, введите:

```
!dict word
```

The first part, i.e. "!dict" **is not** case sensitive.

The bot will then give you the Oxford Dictionary (or Urban Dictionary; if the word does not exist in the Oxford Dictionary) definition of the word as a comment reply.

### Пример:

> !dict what is love

**Определение:**

Детка, не делай мне больно ~ Не делай мне больно ~ больше.

**Пример:**

Dude1: Bruh, what is love? Dude2: Baby, dont hurt me, dont hurt me- no more! Dude1: dafuq?

**Источник:** https://www.urbandictionary.com/define.php?term=what%20is%20love.

---

<sup>Бип-буп. Я бот. Если есть какие-либо вопросы, свяжитесь с моим <a href="https://www.reddit.com/message/compose/?to=PositivePlayer1&subject=/u/Wordbook_Bot">Мастером</a></sup>

<sup>Want to make a similar reddit bot? Check out: <a href="https://github.com/kylelobo/Reddit-Bot">GitHub</a></sup>

## 🏁 Начало работы<a name="getting_started"></a>

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See [deployment](#deployment) for notes on how to deploy the project on a live system.

### Предпосылки

Что нужно для установки программного обеспечения и как их установить.

```
Give examples
```

### Установка

Пошаговая серия примеров, рассказывающих, как запустить среду разработки.

Скажите, какой будет шаг

```
Give the example
```

И повторить

```
until finished
```

Закончите примером получения некоторых данных из системы или использования их для небольшой демонстрации.

## 🚀 Развертывание собственного бота<a name="deployment"></a>

Чтобы увидеть пример проекта по развертыванию бота, просмотрите мою собственную конфигурацию:

- **Heroku** : https://github.com/kylelobo/Reddit-Bot#deploying_the_bot

## ⛏️ Построен с использованием<a name="built_using"></a>

- [PRAW](https://praw.readthedocs.io/en/latest/) - Python Reddit API Wrapper
- [Heroku](https://www.heroku.com/) - SaaS hosting platform

## ✍️ Авторы<a name="authors"></a>

- [@kylelobo](https://github.com/kylelobo) - Idea & Initial work

See also the list of [contributors](https://github.com/kylelobo/The-Documentation-Compendium/contributors) who participated in this project.

## 🎉 Благодарности<a name="acknowledgement"></a>

- Hat tip to anyone whose code was used
- Вдохновение
- Ссылки
