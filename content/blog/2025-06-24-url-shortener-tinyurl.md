---
layout: blog
title: url shortener tinyurl
date: 2025-06-24T15:21:42.309Z
---
**url-shortener-tinyurl** was created as a Python Flask web application that provides a user-friendly interface for shortening URLs using the TinyURL API. The app features a modern, Apple-inspired design and allows users to input a long URL, which is then shortened and displayed on the page. Additionally, each time a URL is shortened, the app sends a notification with the shortened URL to a specified Slack webhook. The shortened tinyurl link does not expire.

T﻿he code is hosted in pythonanywhere by just copying the app.py and requirements.txt. I had to run pip install -r requirements command to install the dependencies from the console. From the Web tab, had to enable the flask application configuration in the wsgi.py file. The pythonanywhere runs for 3 months, then need to click a button to enable it again. A reminder will be sent to the email.