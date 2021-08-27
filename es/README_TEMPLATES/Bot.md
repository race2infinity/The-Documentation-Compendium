<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="https://i.imgur.com/FxL5qM0.jpg" alt="Bot logo"></a>
</p>

<h3 align="center">Nombre del Bot</h3>

<div align="center">

  [![Status](https://img.shields.io/badge/status-active-success.svg)]()
  [![Platform](https://img.shields.io/badge/platform-reddit-orange.svg)](https://www.reddit.com/user/Wordbook_Bot)
  [![GitHub Issues](https://img.shields.io/github/issues/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/issues)
  [![GitHub Pull Requests](https://img.shields.io/github/issues-pr/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/pulls)
  [![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center"> 🤖 Unas cuantas lineas describiendo que hace el bot.
    <br>
</p>

## 📝 Tabla de contenido
- [📝 Tabla de contenido](#-tabla-de-contenido)
- [🧐 Acerca de <a name = "about"> </a>](#-acerca-de--)
- [🎥 Demostración <a name = "demo"> </a>](#-demostración--)
- [💭 Cómo funciona <a name = "working"> </a>](#-cómo-funciona--)
- [🎈 Uso <a name = "usage"> </a>](#-uso--)
  - [Ejemplo](#ejemplo)
- [🏁 Comenzando <a name = "getting_started"> </a>](#-comenzando--)
  - [Requisitos previos](#requisitos-previos)
  - [Instalación](#instalación)
- [🚀 Implementación de su propio bot <a name = "deployment"> </a>](#-implementación-de-su-propio-bot--)
- [⛏️ Creado con <a name = "built_using"> </a>](#️-creado-con--)
- [✍️ Autores <a name = "authors"> </a>](#️-autores--)
- [🎉 Agradecimientos <a name = "acknowledgement"> </a>](#-agradecimientos--)

## 🧐 Acerca de <a name = "about"> </a>

Escribe entre 1 y 2 párrafos que describan el propósito de tu bot.

## 🎥 Demostración <a name = "demo"> </a>

![En funcionamiento](https://media.giphy.com/media/20NLMBm0BkUOwNljwv/giphy.gif)

## 💭 Cómo funciona <a name = "working"> </a>

El bot primero extrae la palabra del comentario y luego busca definiciones de palabras, parte del discurso, ejemplo y fuente de la API del Diccionario Oxford.

Si la palabra no existe en el Diccionario Oxford, la API de Oxford devuelve una respuesta 404 en la que el bot intenta obtener resultados de la API del Diccionario Urbano.

El bot usa la API Pushshift para buscar comentarios, el módulo PRAW para responder a los comentarios y Heroku como servidor.

Todo el bot está escrito en Python 3.6

## 🎈 Uso <a name = "usage"> </a>

Para usar el bot, escriba:

```
! dict palabra
```

La primera parte, es decir, "! Dict" ** no distingue entre mayúsculas y minúsculas.

El bot le dará la definición de la palabra en el Diccionario Oxford (o Urban Dictionary, si la palabra no existe en el Diccionario Oxford) como respuesta a un comentario.

### Ejemplo

>! dict que es el amor

**Definición:**

Bebé, no me lastimes ~
No me hagas daño ~ no más.

**Ejemplo:**

Amigo1: Bruh, ¿qué es el amor?
Dude2: Cariño, no me hagas daño, no me hagas daño, ¡no más!
Amigo1: ¿dafuq?

**Fuente:** <https://www.urbandictionary.com/define.php?term=what%20is%20love>

---

<sup> Bip boop. Soy un bot. Si hay algún problema, comuníquese con mi [Maestro](https://www.reddit.com/message/compose/?to=PositivePlayer1&subject=/u/Wordbook_Bot) </sup>

<sup> ¿Quieres hacer un bot de reddit similar? Echa un vistazo a: [GitHub](https://github.com/kylelobo/Reddit-Bot) </sup>

## 🏁 Comenzando <a name = "getting_started"> </a>

Estas instrucciones le proporcionarán una copia del proyecto en funcionamiento en su máquina local con fines de desarrollo y prueba. Consulte [implementación](#implementación) para obtener notas sobre cómo implementar el proyecto en un sistema en vivo.

### Requisitos previos

Qué necesita para instalar el software y cómo instalarlo.

```
Dar ejemplos
```

### Instalación

Una serie de ejemplos paso a paso que le indican cómo ejecutar un entorno de desarrollo.

Di cuál será el paso

```
Da el ejemplo
```

Y repetir

```
hasta que termine
```

Termine con un ejemplo de cómo sacar algunos datos del sistema o usarlos para una pequeña demostración.

## 🚀 Implementación de su propio bot <a name = "deployment"> </a>

Para ver un proyecto de ejemplo sobre cómo implementar su bot, consulte mi propia configuración:

+ **Heroku**: <https://github.com/kylelobo/Reddit-Bot#deploying_the_bot>

## ⛏️ Creado con <a name = "built_using"> </a>

+ [PRAW](https://praw.readthedocs.io/en/latest/) - Envoltorio de API de Python Reddit
+ [Heroku](https://www.heroku.com/) - Plataforma de alojamiento SaaS

## ✍️ Autores <a name = "authors"> </a>

- [@kylelobo](https://github.com/kylelobo) - Idea y trabajo inicial
- [@FanchiniRudolf](https://github.com/FanchiniRudolf) - Traducción al español

Consulte también la lista de [contribuyentes](https://github.com/kylelobo/The-Documentation-Compendium/contributors) que participaron en este proyecto.

## 🎉 Agradecimientos <a name = "acknowledgement"> </a>

- Apreciación para cualquier persona cuyo código se haya utilizado
- inspiración
- referencias
