# TO-DO App

## Table of Contents
1. [Introduction](#introduction)
2. [Project Overview](#project-overview)
3. [Getting Started](#getting-started)
4. [Code Structure](#code-structure)
5. [Dependencies](#dependencies)
6. [Code Refactoring](#code-refactoring)
7. [Deployment](#deployment)
8. [Usage](#usage)
9. [License](#license)

## Introduction
Welcome to the documentation for the TO-DOIT App, a simple and refactored project designed to manage your tasks efficiently. This document provides an overview of the project, its code structure, refactoring details, clean code practices, design patterns, deployment information, and usage instructions.

## Project Overview
The TO-DOIT App is a web-based application developed to help users manage their tasks by providing a user-friendly interface for adding, editing, and deleting tasks. The app also supports task filtering based on status (All, Pending, Completed) and incorporates a theme switcher for a personalized user experience.

## Getting Started
To get started with the TO-DOIT App, follow these steps:

### Prerequisites
Make sure you have the following installed:
- A modern web browser (e.g., Chrome, Firefox, Safari)
- An internet connection (for fetching external dependencies)

### Installation
1. Clone the Repository:
   ```sh
   git clone git@github.com:abdellatif-laghjaj/todo-list.git
cd todo-list
Open index.html in a Browser:
Open the index.html file in your preferred web browser.
Code Structure
The project follows a modular and organized structure to enhance readability, maintainability, and scalability. Key components include:

HTML (index.html): The main structure of the web page.
CSS (style.css): Styles to define the appearance of the web page.
JavaScript (main.js): Logic for handling user interactions, managing tasks, and implementing theme switching.
Fonts (Poppins): Imported from Google Fonts for consistent typography.
Dependencies
Tailwind CSS: Used for styling the components. It's linked through CDN in the index.html file.
Daisy UI: A CSS library for UI components, linked through CDN.
Boxicons: Icons library, linked through CDN.
Google Fonts (Poppins): Font used for the app, linked in the style.css file.
Code Refactoring
Code Smells Addressed:

Monolithic Structure
Global Functions
HTML Manipulation in Multiple Places
Lack of Error Handling
SOLID Violations Addressed:

Single Responsibility Principle (SRP)
Open/Closed Principle (OCP)
Dependency Inversion Principle (DIP)
Design Pattern Violations Addressed:

Observer Pattern for Event Handling
Strategy Pattern for Task Formatting
Singleton Pattern for Theme Handling
Class Responsibilities:

TodoItemFormatter
TodoManager
UIManager
ThemeSwitcher
