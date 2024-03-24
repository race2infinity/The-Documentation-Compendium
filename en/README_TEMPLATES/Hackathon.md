<p align="center">
  <a href="" rel="noopener">
 <img src="https://i.imgur.com/AZ2iWek.png" alt="Project logo"></a>
</p>
<h3 align="center">Project Title</h3>

<div align="center">

  [![Hackathon](https://img.shields.io/badge/hackathon-name-orange.svg)](http://hackathon.url.com) 
  [![Status](https://img.shields.io/badge/status-active-success.svg)]() 
  [![GitHub Issues](https://img.shields.io/github/issues/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/issues)
  [![GitHub Pull Requests](https://img.shields.io/github/issues-pr/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/pulls)
  [![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE.md)

</div>

---

<p align="center"> Few lines describing your project.
    <br> 
</p>

## 📝 Table of Contents
- [Problem Statement](#problem_statement)
- [Idea / Solution](#idea)
- [Dependencies / Limitations](#limitations)
- [Future Scope](#future_scope)
- [Setting up a local environment](#getting_started)
- [Usage](#usage)
- [Technology Stack](#tech_stack)
- [Contributing](../CONTRIBUTING.md)
- [Authors](#authors)
- [Acknowledgments](#acknowledgments)

## 🧐 Problem Statement <a name = "problem_statement"></a>
It is useful to design and follow a specific format when writing a problem statement. While there are several options
for doing this, the following is a simple and straightforward template often used in Business Analysis to maintain
focus on defining the problem.

- IDEAL: This extension would allow people to enter info about what kind of email they are trying to write and recieve an AI generated text that resembles an email in the style of ECE Department members.
- REALITY: This extension allows people to enter info about what kind of email they are trying to write and recieve an AI generated text that resembles an email in the style of Nanccy (the Assistant to the ECE Department) and our team member Atika.
- CONSEQUENCES: The overall function of the extension is still able to write emails based on our prompts, however the range of styles are more limited, which could affect how many people find this useful.

## 💡 Idea / Solution <a name = "idea"></a>
Our idea was for there to be an easy way to immediately have written emails in specific styles.

The solution became making an extension that utilizes Gemini AI and emails that we fed into it to be able to generate these emails through Chrome.

## ⛓️ Dependencies / Limitations <a name = "limitations"></a>
We did not have enough data to make styles for Dr. Polikar or other ECE faculty members. This affected the amount of styles we were able to implement.

## 🚀 Future Scope <a name = "future_scope"></a>
Given enough data, we could create far more styles of emails meant to match the personalities of other people's emails.

## 🏁 Getting Started <a name = "getting_started"></a>
To run Persona AI locally, follow these steps:

### Prerequisites

- Google Chrome Browser

- Node.js and npm installed

### Installing

1. Clone the repository:

   ```
   git clone https://github.com/skywolfmo/personaai
   ```

2. Navigate to the project directory and install dependencies:

   ```
   npm install
   ```
3. Build the project:

   ```
   npm run build
   ```

## 🎈 Usage <a name="usage"></a>
To use the AI functionality of the Persona AI Chrome extension, you will need to obtain an API key from the Gemini Pro website by Google. Here's a brief summary of how to get the API key:

1. Visit the Gemini Pro API website: [Google Gemini Pro API](https://makersuite.google.com/app/apikey).
2. Follow the instructions to register and create an API key.
3. Once you have the API key, enter it into the top of Persona AI extension and click on Save API Key, this will save it in the local storage.

This API key is essential for enabling the AI features in the extension. Make sure to keep it secure and follow Google's guidelines for API usage.

## ⛏️ Built With <a name = "tech_stack"></a>
- [MongoDB](https://www.mongodb.com/) - Database
- [Express](https://expressjs.com/) - Server Framework
- [VueJs](https://vuejs.org/) - Web Framework
- [NodeJs](https://nodejs.org/en/) - Server Environment

## ✍️ Authors <a name = "authors"></a>
- [@Atik666](https://github.com/Atik666) - Idea & Initial work
- [@LeannamJ](https://github.com/LeannamJ) - Idea & Initial work
- [@raduli92](https://github.com/raduli92) - Idea & Initial work
- [@skywolfmo](https://github.com/skywolfmo) - Idea & Initial work

See also the list of [contributors](https://github.com/skywolfmo/The-Documentation-Compendium/contributors) 
who participated in this project.

## 🎉 Acknowledgments <a name = "acknowledgments"></a>
- Google's Gemini Pro API for providing AI capabilities.
- We used Bard and ChatGPT to guide us through the process of creating this extension
- All contributors who have helped shape Persona AI.
- https://github.com/kylelobo/The-Documentation-Compendium
