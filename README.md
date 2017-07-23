# Learning HTML

## Prerequisites

You need the following installed:

- an IDE, e.g. [Visual Studio Code](https://code.visualstudio.com/)
- [git command line client](https://git-scm.com/downloads)
- a [github](http://github.com) account

## Set-up

## Getting started

- Fork this project into your github account
- Clone your copied project to your workspace

`git clone https://github.com/<your_github_userid>/HtmlCssTutorial.git`

## Introduction to Markup

HTML files are used across the internet to generate the content in web pages.

They consist of the following top-level components:

- an HTML declaration: `<!DOCTYPE html>`. This just tells the browser that this is an HTML document. There are different forms of HTML declarations, this is the one for HTML 5.
- a `<head></head>` section, with information about the page - this is not visible on the final page
- a `<body></body>` section, that contains everything that is visible in the page

HTML stands for HyperText Markup Language. Markup is any form of structured text that describes how something should be displayed. This page is written in a different form of markup, called (confusingly) Markdown.

The markup in HTML consists of `elements`, that have an opening tag and a closing tag. We have already seen three such elements: `html`, `head` and `body`.

Opening tags look like this `<html>` and closing tags look like this `</html>`. Everything in between is the element's `content`. This content can be other `elements`, or just plain text.

Elements often (but not always) include `attributes`, as `key="value"` pairs. These attributes are included inside the opening tag, separated by spaces: `<p class="highlight">`.

## First exercise

Try adding a few elements to the file `index.html`.

- a title element inside `<head></head>`. The content of the element is the title text.
- a level one header element `<h1>` inside `<body></body>`, containing the text `My First HTML Page`

Open this file up in the browser and take a look.

If you can't see the title, that's because it's not inside the body element, so not contained in the page. You should be able to see it somewhere outside of the page though.

## Links

- [List of HTML 5 tags](https://www.w3schools.com/tags/default.asp)
