# Horiseon Accessibility Refactoring

## Introduction and Purpose:

This was my first codebase refactoring challenge at the full stack webdev bootcamp. I used it as an opportunity to get acquainted with what accessibility means in the context of modern web design and how screen readers and other assistive devices interpret webpages, as well as to practice writing semantic HTML along with associated CSS styling.


## Scenario:

A fictional marketing agency named 'Horiseon' requires a codebase that follows accessibility standards, for the sake of accessibility as such, and to optimise its own website for search engines.

## Technical Overview:

The original codebase was constructed almost entirely from div elements styled by associated custom classes in the linked stylesheet. I sought to replace these with semantic elements while taking care to preserve the site's original behaviour precisely.

In the process, I eliminated redundancies in the CSS and fixed a navigational issue. I also reordered the CSS file to better correspond with the markup.


## Results:

The refactored site is currently live on [GitHub Pages](https://tadcos29.github.io/horiseon-accessibility-refactor/) ([Screenshot available.](./assets/images/live-site-screenshot.png))

The GitHub repository for the project is: https://github.com/tadcos29/horiseon-accessibility-refactor

## Potential Issues:

* The [mock-up screenshot](./assets/images/demo-site-screenshot.png) provided as part of the user story does not include a footer with the copyright information. I chose to follow the screenshot precisely and hide the footer element with styling, despite the likelihood of this being undesirable behaviour. It would likely be reverted in the next iteration cycle.

* The scenario-oriented acceptance criteria for the project called for 'accessible alt attributes' for 'icon and image elements'. In the case of icon elements, which are purely decorative, the Web Accessibility Initiative advises that a null attribute is, in fact, the accessible option. I chose to follow this advice.


