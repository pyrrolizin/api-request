<h1 align="center">Welcome to my api-request collection 👋</h1>
<p>
  <img alt="Finished Projects" src="https://img.shields.io/badge/finished_projects_so_far-5-blue.svg?cacheSeconds=25920" />
  <a href="https://github.com/pyrrolizin/api-request/blob/master/LICENSE" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-green.svg" />
  </a>
</p>

This repository is a documentation of my learning and training journey and can also be used as a starter for a webapp project or as a cheat sheet for future projects.

The goal is to recreate the same webapp project in different languages, web design patterns and frameworks.

## 📖 Table of contents

* [List of Features](#🔹-list-of-features)
  * [Frontend](#🖥-frontend)
  * [Backend](#💻-backend)
  * [Documentation](#📔-documentation)
* [Demos so far](#☀️-demos-so-far)
  * [Used Languages and more](#💬-used-languages)

## ✨ Demo (OpenWeatherMap-Api - Current weather in Stuttgart, Germany)

Screenshot from [astro-api-request](https://github.com/pyrrolizin/astro-api-request):

![screenshot of the demo application](screenshot.png)

## 🔹 List of Features

All of the projects have to fulfil the following minimal features and functions.

**👨‍💻💬 User Stories:**

* As a user I want to fetch the current weather conditions and temperature from Stuttgart (Germany).
* As a developer I want to have clear instructions on how to set up the project and I want to have the API key hidden from the users
* As a api provider I want to have the result of the request cached for 5 minutes in the backend

*Optional or nice to have features are in italic.*

### 🖥 Frontend

* *fetch the current condition and the temperature* (not if SSR)
* present the current condition and the temperature to the user
* use the same template with bootstrap for all projects
* the template must be responsive and mobile first
* round the temperature to one decimal place

### 💻 Backend

* save the API_KEY in configuration file *and in environment variables*
* start a web server
* present the frontend to the user
* hide the api key from the user / client
* fetch the current weather for Stuttgart (Germany) from [openweathermap](https://openweathermap.org/api)
* cache for 5 minutes the response from openweathermap in memory

### 📔 Documentation

* screenshot from the frontend
* complete instructions in README.md-file containing:
  * dependencies
  * how to install modules
  * how to configure the api key
  * how to start the server
  * *how to compile/pack the web application for deployment*
* MIT license

## ☀️ Demos so far

| Repository        | Primary Language(s)   | Web design pattern   | Frontend   | Backend   | Comment
| ---               | ---  | --- | ---- | ---- |---- | 
| [astro-api-request](https://github.com/pyrrolizin/astro-api-request) | Astro / TypeScript | SSR | Astro | Astro | New framework. Very nice! |
| [gin-api-request](https://github.com/pyrrolizin/gin-api-request)   | GoLang | SSR | Gin Template | Gin Framework   | experimental framework    |
| [flask-api-request](https://github.com/pyrrolizin/flask-api-request) | Python | SSR | Jinja Template| Python Flask  | first project     |
| [nextjs-api-request](https://github.com/pyrrolizin/nextjs-api-request) | Next.js / TypeScript | REST-API with Client | React TSX | Next.js | Bootstrap 5 and yarn 3 with zero install  |
| [spring-api-request](https://github.com/pyrrolizin/spring-api-request) | Java (Spring Boot) | REST-API with Client | Vue.js | Spring MVC | maven   |

### 💬 Used Languages

![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)

### 🎨 Frontend Tools

![Bootstrap](https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white)
![Jinja](https://img.shields.io/badge/jinja-white.svg?style=for-the-badge&logo=jinja&logoColor=black)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Vue.js](https://img.shields.io/badge/vuejs-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D)

### ⚙️ Backend Tools

![Astro](https://img.shields.io/badge/Astro-%239146FF?style=for-the-badge)
![Gin](https://img.shields.io/badge/gin-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)

### 🛠 Development Tools

![NPM](https://img.shields.io/badge/NPM-%23000000.svg?style=for-the-badge&logo=npm&logoColor=white)
![Insomnia](https://img.shields.io/badge/Insomnia-black?style=for-the-badge&logo=insomnia&logoColor=5849BE)
![Yarn](https://img.shields.io/badge/yarn-%232C8EBB.svg?style=for-the-badge&logo=yarn&logoColor=white)
![Eclipse](https://img.shields.io/badge/Eclipse-FE7A16.svg?style=for-the-badge&logo=Eclipse&logoColor=white)
![Neovim](https://img.shields.io/badge/NeoVim-%2357A143.svg?&style=for-the-badge&logo=neovim&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)

### 🖥 Developed on

![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![iOS](https://img.shields.io/badge/iOS-000000?style=for-the-badge&logo=ios&logoColor=white)
![macOS](https://img.shields.io/badge/mac%20os-000000?style=for-the-badge&logo=macos&logoColor=F0F0F0)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)

## 👋

Badges from <https://github.com/Ileriayo/markdown-badges> and <https://shields.io/>
