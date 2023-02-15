# fast-api-crud-web
Updated: 2022-01-18

https://shinichiokada.medium.com/ (Building a Website Starter with FastAPI).

# Overview
A static simple website ready to deploy. This repo includes all the file and it is ready to deploy to Heroku. How to Deploy a FastAPI App on Heroku for Free

.env

.gitignore

app

Procfile

README.md

requirements.txt

runtime.txt

static

templates

# Requirement

See requirements.txt for updates.

requests==2.27.1

fastapi==0.72.0

uvicorn==0.17.0

python-dotenv==0.19.2

aiofiles==0.8.0

python-multipart==0.0.5

jinja2==3.0.3

Markdown==3.3.6

pytest==6.2.5

# Installation & Usage

$ git clone git@github.com:shinokada/fastapi-web-starter.git

$ cd fastapi-web-starter

# install packages

$ pip install -r requirements.txt

# start the server

$ uvicorn app.main:app --reload --port 8080

Visit http://127.0.0.1:8080/.

Starting

# Features
Menu

Unsplash

Accordion

Markdown pages

# Test

All tests are under tests directory.

Change the directory

$ cd fastapi-web-starter

Run tests

$ pytest -v
