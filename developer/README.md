# Coding Interview Assignment

This assignment will be used as follows:

1. Does the code work and meet the requirements specified below?
2. It may be used to provide a conversation piece for another stage of interviews.

## Objectives

- Write a crawler that hits this endpoint and then proceeds to navigate to each link.
- The application should detect circular links to prevent an infinite loop.
- The application should use Java. Spring is acceptable too.
- There must be sufficient tests.

## Requirements

- Crawl all the links (below) and print out summary statistics at the end:
	- total number of http requests performed throughout the entire application
	- total number of successful requests
	- total number of failed requests (hint: think about what makes something successful or failed)
- You may use gradle, maven, docker, makefile, etc. --> use of gradle/maven wrappers is encouraged.

Starting Point: https://raw.githubusercontent.com/OnAssignment/compass-interview/master/data.json

## Deployment

- Send us a link to your solution's git repo.
- Expect us to build, test, packaging, and run your code.

## What we are looking for?

- We want to see what you would produce as a working product.
- We want to see what you value (e.g. clean code, 12-factor, dry, solid, verbose, terse, etc.).
- We want to see how you think about all phases of developing software: building, testing, running, deploying
- Any amount of building and packaging in order to run is fine; however, the overall goal is to run with **minimal user interaction**. (i.e. one command is usually nice, but not required)
