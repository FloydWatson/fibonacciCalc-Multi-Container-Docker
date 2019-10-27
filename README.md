# fibonacciCalc - Multi-Container - Docker

## Overview

This is an over the top fibonacci calculator. It will Utilize React, Express, Redis and Postgres.
The goal of this application is to better understand multi container deployment.

## Deploy

to deploy as dev:
    Client standalone:
        docker build -f Dockerfile.dev .
        docker run -p 3000:3000 "id"
