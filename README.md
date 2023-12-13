# Project Landing Page
Welcome to the source code repository for the Climate Mind organization's landing page, accessible at climatemind.org. The website serves as a comprehensive platform detailing our mission, approach, team, and more.

## How to Deploy Changes to Production
The website gets deployed through GitHub Pages. Feel free to look at the details in the repository settings under *Pages*. This makes it very easy to update the website. Just apply the necessary changes to the *index.html* and *styles.css* files, create a pull request and merge it into the main branch. GitHub will pick up the changes automatically.

## Historical Information for the climatemind.org Repositories
Originally, the website was written with the template language [pug](https://www.npmjs.com/package/pug) and made use of [gulp](https://www.npmjs.com/package/gulp) to automate some tasks. It was necessary to use an old npm version (8.17.0). There was also an attempt from another programmer to re-write the website using [gatsby](https://www.npmjs.com/package/gatsby), but it seems like it wasn't finished.

To make things easier, I (with ChatGPT) re-wrote the website using plain, simple HTML, CSS and JavaScript. Reasons for that are:
- We don't rely on dependencies that are likely to become outdated soon.  
HTML and CSS are the web standards and won't change for a long time.
- With that simple technology stack, it'll be easy for other programmers in the future to make changes
- Deploying doesn't need steps in between, the HTML and CSS go directly into production without any build steps


