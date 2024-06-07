# Programming-Language

This project was implemented by following step-by-step instructions from [this YouTube playlist](https://youtube.com/playlist?list=PL_2VhOvlMk4UHGqYCLWc6GO8FaPl8fQTh&si=pSsXp7lqzhN690Dj).

## Overview

In this project, we learned to build a basic yet functional programming language in JavaScript and TypeScript.

## Features

- **Parser Development**: Understand the fundamental concepts of parsing and building a syntax tree.
- **Interpreter Design**: Learn how to execute the parsed code.
- **JavaScript and TypeScript Integration**: Utilize the strengths of both languages in developing the language.

## Prerequisites

To run this language, you need to have the following installed:

1. **Deno Extension for VS Code**: Install it from [here](https://marketplace.visualstudio.com/items?itemName=denoland.vscode-deno).
2. **Deno**: Install it from [here](https://deno.com/).

## Getting Started

1. **Clone the repository**: Clone this project to your local machine.
2. **Install Deno**: Follow the instructions on the [Deno website](https://deno.com/) to install Deno on your computer.
3. **Install Deno Extension for VS Code**: Add the Deno extension to your Visual Studio Code from [this link](https://marketplace.visualstudio.com/items?itemName=denoland.vscode-deno).

## Running the Project

To run the language, navigate to the project directory in your terminal and execute the following command:

```sh
deno run -A main.ts
```

## Project Structure

- `main.ts`: The main entry point for running the language.
- `parser.ts`: Contains the parser logic.
- `interpreter.ts`: Contains the interpreter logic.
- `lexer.ts`: Contains the lexer logic.