# Docker compose Documentaion

## 1. Overview

When using Docker extensively, the management of several different containers quickly becomes cumbersome.

Docker Compose is a tool that helps us overcome this problem and **easily handle multiple containers at once.**

In this tutorial, we'll have a look at its main features and powerful mechanisms.

## 2. The YAML Configuration

In short, Docker Compose works by applying many rules declared within a **single docker-compose.yml configuration file.**

These **YAML** rules, both human-readable and machine-optimized, provide us an effective way to snapshot the whole project from ten-thousand feet in a few lines.

Almost every rule replaces a specific Docker command so that in the end we just need to run:

`docker-compose up`
