<div align="center">
  <img src="https://github.com/mbednarek98/ejudge/blob/master/res/logo.png?raw=true" width="250" alt="eJudge Logo" />

  # eJudge

  
  <a href="" target="_blank"><img src="https://img.shields.io/badge/license-MIT-green" alt="Package License" /></a>
  <img src="https://dcbadge.vercel.app/api/shield/247463720337276929?style=flat" alt="Discord" />
</a>

A Node.js-based web application for legal trial case management, leveraging Express JS and MySQL for efficient case handling. <br>    Designed for seamless operation, it supports case creation, modification, and deletion within a Dockerized environment for easy setup and deployment.

</div>

## 📑 Table of Contents
1. [Prerequisites](#🔑-prerequisites)
2. [Installation](#⚙️-installation)
3. [Usage](#🚀-usage)
4. [Database Diagram](#💬-database-diagram)
5. [Screenshots]()
6. [License](#📕-license)

## ✨ Features

- Legal trial case CRUD operations.
- Integrated MySQL database management via Sequelize ORM.
- Real-time case data processing with Express JS and Node JS.
- Integrated phpMyAdmin for intuitive database management.

## 🔑 Prerequisites

Before you begin, ensure you have the following installed:
- Docker Desktop: [Download](https://www.docker.com/products/docker-desktop/)
- Node.js (v20+): [Download](https://nodejs.org/en/)
- NPM (included with Node.js): [Info](https://www.npmjs.com/)
- IDE: [Visual Studio Code](https://code.visualstudio.com/) or [VSCodium](https://vscodium.com/)

## ⚙️ Installation

### 1. Clone the Repository
First, clone the repository to your local machine:

```bash
$ git clone https://github.com/mbednarek98/ejudge.git

$ cd ejudge

$ code .            # Optional: Open in Visual Studio Code
```

### 2. Install Dependencies

Navigate to the project directory and install the required dependencies:

```bash
$ npm install       # Installs all dependencies saved in package.json
```

### 3. Docker Compose
```bash
$ cd docker

$ docker-compose up    # Creates phpMyAdmin and MongoDB containers
```


## 🚀 Usage
Run the application:

```bash
$ npm start        # Runs the application
```

## 💬 Database Diagram

<div align='center'>
  
<img src="https://github.com/mbednarek98/ejudge/blob/master/res/db_diagram.png?raw=true"  alt="Database diagram" />

</div> 

## 📕 License

This project is licensed under the [MIT license](LICENSE)