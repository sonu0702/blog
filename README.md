# blog

# Project Run Guide

This project is a Node.js and TypeScript application configured to run locally.

## Prerequisites

Ensure you have the following installed on your local machine:
* **Node.js**: Version `10.x.x` (as specified in `package.json`), can run with latest Node.js 
* **npm**: Installed automatically with Node.js

## Installation

Install the required dependencies using npm:
```bash
npm install
```
*Note: This command will automatically trigger the `prepare` script, which compiles the TypeScript code into JavaScript.*

## Available Scripts

In the project directory, you can run the following commands:

### Build the Project
Compiles the TypeScript source code into JavaScript inside the `lib/` directory.
```bash
npm run gcp-build
```

### Start the Application
Runs the compiled application from the entry point (`lib/server.js`).
```bash
npm start
```
