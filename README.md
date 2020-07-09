# reveal-ucb-theme
A CU theme for presentations using Reveal.js 

### Setup
- [Install Reveal.js](https://revealjs.com/installation/#full-setup) using the recommened install
- Download the ````ucb-dark.css```` file
- Place this file in the ````dist/theme```` directory
- In index.html, change the the stylesheet with the ````id="theme"```` to have an href value of ````dist/theme/ucb-dark.css````
- Also add this markup to index.html directly under the <body> tag to give the slides a nice footer.
````
  <img src="/images/cu-boulder-logo-text-white.svg" alt="cu footer logo" />
````
- Add the ````favicon.ico```` to the project root
- Add the ````/images```` directory with the .svg inside to the root as well. 

### Editing the Theme
The official documentation for editing a Reveal theme can be [found here](https://github.com/hakimel/reveal.js/blob/master/css/theme/README.md). The steps below summarize how to edit this theme using those steps.
- Download the .css and .scss file
- Place the .scss file in the ````css/theme/source````
- Change the theme to ````ucb-dark.css````
- Edit the file as needed. Reveal does live SCSS updates, so no need convert the file to CSS
- When you're done, do ````npm run build```` to generate a CSS file. 
- Replace the CSS/SCSS files in this repo with the new ones
