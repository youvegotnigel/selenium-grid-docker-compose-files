# Selenium Grid with Docker Compose

This repository contains a Docker Compose setup for running a Selenium Grid with Chrome, Edge, and Firefox nodes. This configuration allows you to run automated tests across multiple browsers in parallel using Selenium.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Setup](#setup)
- [Usage](#usage)
- [Configuration](#configuration)
- [Environment Variables](#environment-variables)
- [Troubleshooting](#troubleshooting)

## Prerequisites

Before you can use this setup, ensure that you have the following installed:

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Setup

1. **Clone the repository**:

   ```sh
   git clone https://github.com/yourusername/selenium-grid-docker.git
   cd selenium-grid-docker
   ```

2. **Create a .env file**:

   ```sh
    cp .env.example .env
    ```


3. **Start the Selenium Grid**:

   ```sh
    docker-compose -f docker-compose.yml up -d
    ```
