# Prerequisites

## Intro

This tutorial will help you setup and install NodeJs, NPM, and a few basic tools for modern javascript development.

## Why

Why do we want to install nodejs or npm? If you want a modern javascript development environment, or want to use a lot of the latest tools and frameworks, you will need node and npm. Node and npm will form part of our tool chain.  

- Gulp? node.
- ExpressJs? yup, node.
- Angular? node again.
- React? still node.
- WebPack? guess what? node.

## Dependencies - Installation / Configuration

- [NodeJs](#nodejs)
- [NPM](#npm)
- [Other Tools](#tools)
- [Visual Studio Code](#visual-studio-code)

### NodeJs

#### Versions

##### LTS - v6

This is the Long Term Support version of NodeJs.

##### Current - v8

The version of NodeJS this guide is using is v8.2.1, but the v6 versions can also be used.

    C:\Users\chrisayers>node -v
    v8.2.1

NodeJs can be found at: [https://nodejs.org/](https://nodejs.org/).  There are additional downloads and installers available at [https://nodejs.org/en/download/current/](https://nodejs.org/en/download/current/). 

### NPM

The version of npm this guide is using is v4.5.0, but earlier v4 versions should work fine.

    C:\Users\chrisayers>npm -v
    4.5.0

#### NPM Packages

- @angular/cli
  - this will be used to setup the initial angular pieces.  You can use the ng command to help scaffold components and services in the angular app.
- webpack
  - this will be used to compile, optimize, and "tree shake" the front end application.  We will also create application and vendor bundles.
- typescript
  - all front end angular development is in typescript

### Visual Studio Code

We are going to install Visual Studio Code.
