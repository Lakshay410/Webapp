# Grocery List Application

This project is a web application built using SAP's UI5 framework. It allows users to create and manage a grocery list by grouping similar items, displaying their prices and quantities, and providing an interface to rate each item. The application greets users with a personalized welcome message.

## Table of Contents

- [Features](#features)
- [Technologies](#technologies)
- [Project Structure](#project-structure)
- [Setup](#setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- *Personalized Greeting*: Displays a customized welcome message for the user.
- *Grocery List Management*: Allows adding, viewing, and organizing grocery items.
- *Price and Quantity Display*: Shows the price and quantity of each item.
- *Item Rating*: Users can rate each item.

## Technologies

- *SAP UI5*: Main framework used for building the UI.
- *JavaScript*: Core programming language.
- *HTML*: Markup language for the structure of the application.
- *CSS*: Styling for the application.

## Project Structure

```plaintext
grocery-list-app/
|-- webapp/
|   |-- css/
|   |   |-- style.css
|   |-- view/
|   |   |-- App.view.xml
|   |   |-- Welcome.view.xml
|   |   |-- List.view.xml
|   |-- controller/
|   |   |-- App.controller.js
|   |   |-- Welcome.controller.js
|   |   |-- List.controller.js
|   |-- model/
|   |   |-- models.js
|   |-- Component.js
|-- index.html
|-- manifest.json
