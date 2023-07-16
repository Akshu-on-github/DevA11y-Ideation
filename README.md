# DevA11y - Ideation Docs
## Inspiration
Nowadays, accessibility overlays are all the rage - a "silver bullet" single line of code to make your website accessible. But the sad truth is that they make websites _less_ accessible by overriding system defaults customized by the user. Despite this, why have only grown in popularity?
The main reason is that, unless accessibility was a consideration at the start of development, it is time-consuming to implement. This project attempts to lend a hand to other projects at late-stage development to meet Level A of the WCAG 2.0 specification.

## What it does
This is a draft of technical documentation created in Figma that lays out some of my ideas about a project that:
- Scrapes a given URL
- Analyzes the code
- Identifies elements that require modifications
- Flags those elements with possible solutions
- Compiles these changes in a checklist

## Suggested Tech Stack
Note: The code was not ready to be submitted, so only the prep documentation is submitted for the hackathon. The docs used *Figma* and *MatLab*
- Angular (Frontend)
- Node (Backend)
- Puppeteer (Webscraper)
- Express
- Firebase (Storage & Deployment)
