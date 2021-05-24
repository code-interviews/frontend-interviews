# Front-end Developer Interview Handbook

## Introduction

This is an open source repository of questions, answers and concepts being exchanged at Front-end developer job interviews these days, neatly journaled by the contributors based on their personal experience. Along with an exhaustive quantity of content, it also focuses on neatly segregating and structuring them so that developers can directly jump to relevant sections.

## Why another repo?

It is true that there exists other repositories already which attempt to provide the most exhaustive set of materials and guide front-end developers to train themselves for job interviews. Yet no resource is entirely complete, some lack proper orientation of the syllabus while some do not provide satisfactory solutions to the problems. Consider this repo as another feather in the hat as we try to fill the gaps. 

**Note:** This repo does not claim to be a one-stop solution for the developers to go from zero to hero overnight. Most questions and answers are kept open-ended for discussions, and you are not required to memorize them verbatim to ace your next interview. It is a humble attempt by the developers, for the developers to improve their thought process :)

## Table of contents
---
* [HTML](#html-interview-questions)
* [CSS](#css-interview-questions)
* [JS](#js-interview-questions)
* [Angular](#angular-interview-questions)
* [React](#react-interview-questions)
* [Node](#node-interview-questions)

## HTML Interview Questions
---
Q. What are meta tags? Can you store custom information in them?

Metadata putting simple is data that describes data. The HTML document contains meta tags <meta> that describe the document — for example who wrote it, and its summary. They are declared in the <head> tag. For example, you may add **description, keywords, author, viewport** and some custom tags.:

	<head>
		<meta name="description" content="Free Web tutorials">
		<meta name="keywords" content="HTML,CSS,JavaScript">
		<meta name="author" content="John Doe">
		<meta name="viewport" content="width=device-width, initial-scale=1.0">
		<meta name="mytag" content="My Tag">
	</head>

Q. Describe some HTML5 features?

Following are some HTML5 tags which were introduced:

**video and audio**

It provides a native video and audio player with basic controls.

	<video width="1024px" height="600px" controls>
		<source src="video-url.mp4" type="video/mp4">
	</video>

	<audio controls autoplay>
		<source src = "/path-to-audio/audio.ogg" type = "audio/ogg" />
	</audio>

**svg**

It can be used to draw vector graphics with shapes, colors, animations and interactivity.

	<svg id = "svgelem" height = "200" xmlns = "http://www.abc.org/2000/svg">
		<circle id = "redcircle" cx = "50" cy = "50" r = "50" fill = "red" />
	</svg>

**header and footer**

As their names suggest you can use them for Navigation purposes. Header stays at the top of the web-page structure whereas footer at the bottom, by convention.

	<!DOCTYPE html>
	<html>
		<head>
			<title>Header Tag</title>
		</head>
		<body>
			<header>
				<h1>This is the heading.</h1>
			</header>
			<main>This is main.</main>
			<footer>This is footer.</footer>
		</body>
	</html>