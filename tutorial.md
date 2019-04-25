## Introduction

In this tutorial, we are going to build a full stack book gathering application using NodeJS, Express, React & SQLite.

## Contents

- [Introduction](#introduction)
- [Contents](#contents)
- [Prerequities](#prerequities)
- [Project Specifications](#project-specifications)
- [Project Architecture](#project-architecture)

## Prerequities

In order to follow this tutorial, you will have to be familiar with the following tools and technologies:

- Javascript
- React
- NodeJS
- SQLite

## Project Specifications

We are going to build a simple book gathering application. The primary functions of the application include:

- User should be presented with a graphical user interface when the application is opened in a web browser.
- User should be able to view and filter through all of the books current stored in the database.
- User should be able to add new books, both individually and in bulk.
- User should be able to edit books, individually or in bulk.
- User should be able to delete books, individually or in bulk.

## Project Architecture

The backend will make use of ExpressJS, which will have access to the SQLite database. We will make use of sequelize as ORM. Since this is a small application, the server and the client are developed in the same git repository. The client is scaffolded out with `create-react-app`. We will use styled-components on the client-side for styling. We will use jest for testing both the server & the client. The client is rendered on the browser. The client is also a PWA so it will try to aggressively cache data for offline usage.
