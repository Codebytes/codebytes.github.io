# Prerequisites

## Intro

This is going to setup an application with .Net Core running Angular 4 with webpack.  All the angular files will be compiled and optimized during build and placed in the wwwroot of the .Net Core application.  All the front end files will be served as **Static Files**.  We are **not** going to use MVC at all.

## Dependencies - Installation / Configuration

- [.Net Core](#.net-core)
- [NodeJs](#nodejs)
- [NPM](#npm)
- [Visual Studio 2017](#visual-studio-2017)

### .Net Core

This guide is written using the .Net Core SDK 1.0.3. You can download all the required bits at [https://www.microsoft.com/net/download/core](https://www.microsoft.com/net/download/core).

    C:\Users\chrisayers>dotnet --info
    .NET Command Line Tools (1.0.3)

    Product Information:
     Version:            1.0.3
     Commit SHA-1 hash:  37224c9917

    Runtime Environment:
     OS Name:     Windows
     OS Version:  10.0.15063
     OS Platform: Windows
     RID:         win10-x64
     Base Path:   C:\Program Files\dotnet\sdk\1.0.3


### NodeJs

The version of NodeJS this guide is using is v7.9.0, but the v6 versions can also be used.

    C:\Users\chrisayers>node -v
    v7.9.0

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

### Visual Studio 2017

Any version of Visual Studio 2017 will do.  If you are developing at home, the Community edition has all the features you need.  If this is for business or enterprise development, the Professional and Enterprise editions add some additional features.

## Source Control / VSTS Configuration

This tutorial series assumes that the application is running in VSTS.  As for source control, you can use git, TFS, or anything supported by VSTS.  We will be creating VSTS Build and Release configurations for this applications.

1. Create a new VSTS Team
1. Setup either GIT or TFS
1. Initialize Repository

