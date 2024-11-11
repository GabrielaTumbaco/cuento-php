# Cuento-PHP 🤖

This repository contains a PHP program that prints a short story about a little robot named Bolt. It's a simple text-based program useful for learning basic PHP programming.

## Description ✍️

The program tells a short story about a small robot named Bolt who embarks on an adventure despite facing challenges like a storm. This story demonstrates the use of `echo` statements in PHP to output text.

## Requirements

- **PHP 7.0** or higher
- **Git** to clone the repository

## How to Clone and Run

To clone this repository to your local machine, use the following commands:

```bash
git clone https://github.com/GabrielaTumbaco/cuento-php.git
cd cuento-php
```
## To run the program:

php cuento.php

## Dockerization 🐋
<ol>
  Step 1: Build the Docker Image

```bash

docker build -t cuentophp .

```
  Step 2: Tag the Image

```bash

docker tag cuentophp gltumbaco/cuentophp:latest
```

  Step 3: Push Image to Docker Hub
```bash
docker push gltumbaco/cuentophp:latest
```
</ol>

## Link to Docker Hub 👩‍💻

Cuento-PHP on Docker Hub: https://hub.docker.com/repository/docker/gltumbaco/cuentophp/general
