---
layout: default
title: API Basics
nav: basics
---

### Getting Started

The current version of the API lives at ```https://api.gsa.gov/v3/path```.

- One example of a way to use it.
- Another example of a way to use it.

#### Versions

| Version | Date | Changes
| ------------- | -------------|
| ```version 1``` | 1/1/2095 | Initial deployment
| ```version 2``` | 3/1/2096 | Changed data structure to fit congressional mandate
| ```version 3``` | 3/1/2099 | Request pattern changed for new requirements

#### Endpoints

| Endpoint | What it does |
| ------------- | -------------|
| ```/citypairs/airfares``` | Returns an array of Airfares based on query parameters
| ```/citypairs/airfares/{id}``` | Returns an array of Airfares based on unique identifier. Array will contain one airfare. (This is just for demonstration purpose. For City Pairs, the ID does not have meaning.)

<body id="basics"></body>
