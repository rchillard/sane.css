# sane.css
CSS reset providing sane defaults.  Sane.css combines three different approaches:

## [HTML 5 Boilerplate](https://github.com/h5bp/main.css)
The best boilerplate on the planet brings a large number of baselines, such as:

- A default color, font-size, and line-height (1.4) on the HTML element
- Setting box-sizing rules to border-box on everything
- Fixing vertical alignment of multimedia elements (audio, canvas, iframe, img, svg, video)

## [Normalize CSS](https://github.com/necolas/normalize.css)
Gold standard in CSS normalization was used to fix issues across browsers, such as:

- Incorrect H1 sizes inside of section and articles elements
- Various font adjustments for elements like b, strong, code, kbd, samp
- Form and button margin and font size adjustments

## [Modern CSS Reset](https://github.com/andy-piccalilli/modern-css-reset)
Andy Bell's CSS reset features several improvements for sanity and accessiblility, such as:

- Body element will always fill the screen and text rendering will be optimized for speed
- A media query for prefers-reduced-motion that removes animation, transition, and scroll behavior

## Known Shortcomings
This stylesheet does not have print styles.  If you need print styles, I recommend you checkout [HTML 5 Boilerplate](https://github.com/h5bp/main.css).

This stylesheet does not accommodate Internet Explorer.  In fact, rules to cover IE that were a part of major influences have been removed.  This is as intentional choice as a result of Microsoft announcing [End of Life for IE](https://docs.microsoft.com/en-us/lifecycle/announcements/internet-explorer-11-end-of-support).

# Contributing
While this stylesheet is primarily here for my personal projects, I'm open to and would love to hear suggested improvements!  Feel free to open an issue to start a discussion or propose an improvement.
