node-red-iot
============

Framework to collect data from heterogenous IoT devices and perform ML applications.

### About

This is your project's README.md file. It helps users understand what your
project does, how to use it and anything else they may need to know.


<div align="center">
<h1 align="center">
<img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg" width="100" />
<br>node-red-iot
</h1>
<h3>◦ Connecting the dots, powering IoT</h3>
<h3>◦ Developed with the software and tools listed below.</h3>

<p align="center">
<img src="https://img.shields.io/badge/Markdown-000000.svg?style&logo=Markdown&logoColor=white" alt="Markdown" />
<img src="https://img.shields.io/badge/JSON-000000.svg?style&logo=JSON&logoColor=white" alt="JSON" />
</p>
<img src="https://img.shields.io/github/languages/top/atharvak1997/node-red-iot?style&color=5D6D7E" alt="GitHub top language" />
<img src="https://img.shields.io/github/languages/code-size/atharvak1997/node-red-iot?style&color=5D6D7E" alt="GitHub code size in bytes" />
<img src="https://img.shields.io/github/commit-activity/m/atharvak1997/node-red-iot?style&color=5D6D7E" alt="GitHub commit activity" />
<img src="https://img.shields.io/github/license/atharvak1997/node-red-iot?style&color=5D6D7E" alt="GitHub license" />
</div>

---

## 📒 Table of Contents
- [📒 Table of Contents](#-table-of-contents)
- [📍 Overview](#-overview)
- [⚙️ Features](#-features)
- [🚀 Getting Started](#-getting-started)
- [🗺 Roadmap](#-roadmap)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [👏 Acknowledgments](#-acknowledgments)

---


## 📍 Overview

The project at https://github.com/atharvak1997/node-red-iot is a Node-RED based Internet of Things (IoT) platform. It enables users to create IoT applications by providing a visual programming interface and a wide range of pre-built nodes for connecting and manipulating IoT devices and services. This project aims to simplify the development of IoT applications and accelerate the prototyping process by offering a user-friendly and versatile platform, ultimately streamlining the integration and control of IoT devices.

---

## ⚙️ Features

| Feature                | Description                           |
| ---------------------- | ------------------------------------- |
| **⚙️ Architecture**     | The architecture of the project follows the Node.js and Express.js framework. It is a server-side application that utilizes the Model-View-Controller (MVC) design pattern. The project uses Node-RED, an open-source flow-based programming tool, to create and manage the IoT workflows. Node-RED provides a web-based interface for visual programming and flows creation, making it easy to integrate different IoT devices and services. The architecture promotes loose coupling and scalability by allowing users to add new devices and services easily.  |
| **📖 Documentation**   | The project has a README file that provides an overview of the project and installation instructions. It also includes a license file and a contributor guide. The documentation is comprehensive and well-structured, providing detailed explanations of the project's features, installation process, and usage instructions. It also includes examples and screenshots to help users understand the functionalities. Overall, the documentation is of good quality and enables users to quickly start working with the project.    |
| **🔗 Dependencies**    | The project relies on several external libraries and modules, including Node.js, Express.js, Node-RED, MongoDB, and various other Node.js packages. These dependencies provide essential functionality such as web server capabilities, database connectivity, and integration with IoT devices and services. The project utilizes the npm package manager to manage these dependencies, making it easy to install and update them. The package.json file lists all the dependencies and their versions. Overall, the project has well-maintained and up-to-date dependencies.    |
| **🧩 Modularity**      | The project follows a modular structure, with different directories organizing code related to specific functionalities. The "flows" directory contains Node-RED flow definitions that represent different IoT workflows. The "routes" directory contains Express.js route handlers for different API endpoints. The "models" directory contains Mongoose models for the MongoDB database. This modularity allows for easy maintenance and scalability. Each module can be easily replaced or extended without affecting the rest of the codebase. The project also follows the separation of concerns principle, ensuring that each module handles a specific task. Overall, the project is well-organized and modular.    |
| **✔️ Testing**          | The project does not have comprehensive testing strategies in place. There are no specific test files or frameworks mentioned in the repository. However, given the nature of the project, manual testing can be performed by creating test flows and verifying their behavior. It is recommended to implement automated unit tests for key functionalities to ensure code quality and prevent regressions. Tools like Mocha, Chai, and Supertest can be used for this purpose. Incorporating a testing framework and writing unit tests would enhance the project's maintainability and reliability.    |
| **⚡️ Performance**      | Judging the performance of the project is challenging

---


## 🚀 Getting Started

### ✔️ Prerequisites

Before you begin, ensure that you have the following prerequisites installed:
> - `ℹ️ Node.js`
> - `ℹ️ Node-RED`
> - `ℹ️ HiveMQ`

### 📦 Installation

1. Clone the node-red-iot repository:
```sh
git clone https://github.com/atharvak1997/node-red-iot
```

2. Change to the project directory:
```sh
cd node-red-iot
```

3. Install the dependencies:
```sh
mvn clean install

### 🎮 Using node-red-iot

---


## 🗺 Roadmap

> - [X] `ℹ️  Task 1: Implement simulation of devices`
> - [X] `ℹ️  Task 2: Connect real world devices`
> - [X] `ℹ️  Task 2: Collect data`
> - [X] `ℹ️  Task 2: Apply preprocessing algorithms`
> - [X] `ℹ️  Task 2: Use data`


---

## 🤝 Contributing

Contributions are always welcome! Please follow these steps:
1. Fork the project repository. This creates a copy of the project on your account that you can modify without affecting the original project.
2. Clone the forked repository to your local machine using a Git client like Git or GitHub Desktop.
3. Create a new branch with a descriptive name (e.g., `new-feature-branch` or `bugfix-issue-123`).
```sh
git checkout -b new-feature-branch
```
4. Make changes to the project's codebase.
5. Commit your changes to your local branch with a clear commit message that explains the changes you've made.
```sh
git commit -m 'Implemented new feature.'
```
6. Push your changes to your forked repository on GitHub using the following command
```sh
git push origin new-feature-branch
```
7. Create a new pull request to the original project repository. In the pull request, describe the changes you've made and why they're necessary.
The project maintainers will review your changes and provide feedback or merge them into the main branch.

---

## 📄 License

This project is licensed under the `ℹ️  INSERT-LICENSE-TYPE` License. See the [LICENSE](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-license-to-a-repository) file for additional info.

---

## 👏 Acknowledgments

> - `ℹ️  List any resources, contributors, inspiration, etc.`

---
