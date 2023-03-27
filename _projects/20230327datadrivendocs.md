---
title: 'Getting Started with D3js'
subtitle: 'Learning to use a Javascript Library for data viz'
date: 2023-03-27 19:30:00
featured_image: '/images/blog_images/2023-03-27-interface.gif'
---

<figure>
  <p align="center">
    <img src="{{site.url}}/images/blog_images/2023-03-15-window.svg" alt="Coding Window" width="25%"/>
  <figcaption> Coding Window.</figcaption>
  </p>
</figure>


# Brief Introduction to D3 (i.e., Data-Driven Documents)

It is fast, it is a great framework and it is free.

> D3 allows you to bind arbitrary data to a Document Object Model (DOM), and then apply data-driven transformations to the document. For example, you can use D3 to generate an HTML table from an array of numbers. Or, use the same data to create an interactive SVG bar chart with smooth transitions and interaction.

I have created a Github Repository to capture much of what I am documenting here to aid in my use of D3.


## Tools Needed


1. You need some sort of IDE (i.e., an integrated development environment), to write out your code.


<figure>
  <p align="center">
    <img src="{{site.url}}https://upload.wikimedia.org/wikipedia/commons/9/9a/Visual_Studio_Code_1.35_icon.svg" alt="Coding Window" width="25%"/>
  <figcaption>Visual Studio Code</figcaption>
  </p>
</figure>


I am going to Visual Studio Code (VSCode). It is a product from Microsoft that seems to be all the rage because it is light-weight(i.e., it doesn't take up much space and processing), and it is appears to be bree at a base level.

2. You will need some sort of web-browser.


<figure>
  <p align="center">
    <img src="{{site.url}}https://upload.wikimedia.org/wikipedia/commons/e/e1/Google_Chrome_icon_%28February_2022%29.svg" alt="Coding Window" width="25%"/>
  <figcaption>Visual Studio Code</figcaption>
  </p>
</figure>


I prefer to use Chrome. It is the browser I use most frequently for my work, and research and for play.


3. You will need a web server. 


A suggested is server is the `python -m htpp.server`.


Generally speaking a server is not needed. However, because the focus of D3 is on interraction, you need to get a sense of what the product will look like and behave once it is put out into the world. A server helps with that process.

> Sometimes it's not necessary. But in general, it's a good idea to replicate the environment that your code will be viewed in so you don't run into unforeseen issues when you publish or unnecessary frustrations due to using an environment not intended for your technology.

> d3 is intended to run in the browser, with some parts of it requiring to be run on a web page for certain browsers. In my experience, the issues that arise from opening a d3 page directly in browser using the file URI, i.e. `file://`, are split into two categories: security and schemeless urls.[^1]


You have a similar issue when using RevealJS for example, with a Development Server that defaults to port 8000 when you run the following:

```
npm start -- --port=8001

```

4. You need the D3 library itself.


### Downloading the D3 Library.

<a href="https://d3js.org/">Data Driven Documents</a>

You can download the latest version there as a folder. Which you can then store in the directory from which you will be creating projects. Then when you need the latest version, simply downloa dthe folder again. 

Alternatively you can link directly to the latest releast copy, via a code snippet.

<script src="https://d3js.org/d3.v7.min.js"></script>

The website also provides a number of examples you can use for practicing.

Do note that the creator Mike Bostock has a number of training tools available through Observable, which is a JavaScript project platform. I don't have a problem with Observable, it also requires some learning which I don't have the capacity for at present. 

## Creating the Basics

Open the terminal within VSCode

touch index.html

[^1]: <a href="https://stackoverflow.com/questions/50583765/why-do-i-need-to-start-a-web-server-to-use-d3">Why do I need to start a web server to use d3?</a>



---
Image Sources:


<a href="https://iconscout.com/lotties/user-interface" target="_blank">User Interface Animated Icon</a> by <a href="https://iconscout.com/contributors/nanoagency">nanoagency</a> on <a href="https://iconscout.com">IconScout</a>

<a href="https://iconscout.com/icons/window" target="_blank">Window Icon</a> by <a href="https://iconscout.com/contributors/jemismali" target="_blank">Jemis Mali</a>
