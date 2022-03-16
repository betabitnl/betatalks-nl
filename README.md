# betatalks.nl

This repo holds the sources of the betatalks.nl main website.

## Tech stack

* API: Azure Functions
* Framework: .NET 6
* Fronted: Blazor Web Assembly (WASM)
* Toolkit: Bootstrap?

## Repository structure

Here's a short explanation of the structure of files and folders in this repository.

### 📋 Readme.md

This file 🤓

### 📁 .azurite

Contains the contents of the [Azurite](https://github.com/Azure/Azurite) emulator to enable you to run everything locally and run unit
tests.

### 📁 API

Azure Functions that implement the API used to make the website dynamic (content, contact, etc).

### 📁 Common

Common stuff shared between the API and the Frontend like helpers and DTO's.

### 📁 Frontend

The Blazor WebAssembly frontend of the [betatalks.nl](https://www.betatalks.nl) website.

### 📁 Tests

All Unit Tests for the project should be under this folder.
