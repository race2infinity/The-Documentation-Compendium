<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="https://i.imgur.com/FxL5qM0.jpg" alt="Bot logo"></a>
</p>

<h3 align="center">Título do Bot</h3>

<div align="center">

  [![Status](https://img.shields.io/badge/status-active-success.svg)]()
  [![Platform](https://img.shields.io/badge/platform-reddit-orange.svg)](https://www.reddit.com/user/Wordbook_Bot)
  [![GitHub Issues](https://img.shields.io/github/issues/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/issues)
  [![GitHub Pull Requests](https://img.shields.io/github/issues-pr/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/pulls)
  [![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center"> 🤖 Descreva o que seu bot faz em apenas algumas linhas.
    <br> 
</p>

## 📝 Índice
+ [Sobre](#sobre)
+ [Demonstração / Protótipo](#demonstracao)
+ [Como Funciona](#como_funciona)
+ [Uso](#uso)
+ [Primeiros Passos](#primeiros_passos)
+ [Realizando o Deploying de Seu Próprio Bot](#deployment)
+ [Feito Com](#feito_com)
+ [TODO](../TODO.md)
+ [Contribuiçōes](../CONTRIBUTING.md)
+ [Autores](#autores)
+ [Agradecimentos](#agradecimentos)

## 🧐 Sobre <a name = "sobre"></a>
Escreva entre 1-2 parágrafos uma descriçāo com o propósito do seu bot.

## 🎥 Demonstração / Protótipo <a name = "demonstracao"></a>
![Como Funciona](https://media.giphy.com/media/20NLMBm0BkUOwNljwv/giphy.gif)

## 💭 Como Funciona <a name = "como_funciona"></a>
Primeiramente, o bot extrái a palavra de um determinado comentário e analíza definiçōes, categoria gramatical, exemplo e fonte para essa palavra na API do Dicionário de Oxford.

Se essa palavra não existe no Dicionário de Oxford, a API de Oxford retorna uma reposta de erro '404' na qual o bot então tenta filtrar resultados da API do Urban Dictionary.

Este bot usa a API Pushshift para filtrar comentários, utiliza também o módulo PRAW para responder os comentários e um servidor Horuko para hospedagem.

Este bot foi escrito usando Python 3.6

## 🎈 Uso <a name = "uso"></a>

Para utilizar o bot, digite:
```
!dict palavra
```
A primeira parte, por exemplo "!dict" **nāo é** sensível a letras maiúsculas e minúsculas.


O bot entāo vai gerar a definiçāo da palavra (baseado na API do Dicionário de Oxford ou Urban Dictionary) como uma resposta-comentário.  

### Exemplo:

> !dict what is love

**Definição:**

Baby, dont hurt me~
Dont hurt me~ no more.

**Exemplo:**

Dude1: Bruh, what is love?
Dude2: Baby, dont hurt me, dont hurt me- no more!
Dude1: dafuq?

**Fonte:** https://www.urbandictionary.com/define.php?term=what%20is%20love

---

<sup>Beep boop. Eu sou um bot. Se surgir algum problema, me contate [Master](https://www.reddit.com/message/compose/?to=PositivePlayer1&subject=/u/Wordbook_Bot)</sup>

<sup>Tá afim de criar um bot similar? Se liga só: [GitHub](https://github.com/kylelobo/Reddit-Bot)</sup>

## 🏁 Primeiros Passos <a name = "primeiros_passos"></a>
Estas intruçōes te darão uma cópia funcional do projeto na sua máquina local para desenvolvimento e testes. Veja [deployment](#deployment) para uma descrição de como realizar o deployment deste projeto online.

### Pré-requisitos

Descreva o que é necessário para instalar este software e como instalá-lo.

```
Cite exemplos
```

### Instalacão

Passo-a-passo com exemplos que reproduzam um estágio de desenvolvimento funcional.

Descreva o passo a ser tomado

```
Dê um exemplo
```

Repita

```
Até terminar
```

Finalize com um exemplos de como os dados são processados ou uma pequena demonstração.

## 🚀 Realizando o Deploying de Seu Próprio Bot <a name = "deployment"></a>
Confira um exemplo de como realizar o deployment de seu bot, estas são as minhas configuraçōes:

+ **Heroku**: https://github.com/kylelobo/Reddit-Bot#deploying_the_bot

## ⛏️ Feito Com <a name = "feito_com"></a>
+ [PRAW](https://praw.readthedocs.io/en/latest/) - Python Reddit API Wrapper
+ [Heroku](https://www.heroku.com/) - Plataforma de Hospedagem SaaS

## ✍️ Autores <a name = "autores"></a>
+ [@kylelobo](https://github.com/kylelobo) - Ideia & Trabalho inicial

Confira também a lista de [contribuidores](https://github.com/kylelobo/The-Documentation-Compendium/contributors) que participaram nesse projeto.

## 🎉 Agradecimentos <a name = "agradecimentos"></a>
+ Agradecimentos a terceiros, autores ou não de código utilizado nesse projeto.
+ Inpiraçōes
+ Referêcias
