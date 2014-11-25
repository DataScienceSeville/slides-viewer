Slides viewer
=============

A viewer for [Remark](https://github.com/gnab/remark) slides, also integrated with [Mathjax](http://www.mathjax.org/). This project was created for rendering the [slides](http://datascienceseville.github.io/slides-viewer/) of the [Data Science Seville](https://github.com/DataScienceSeville) group.

The viewer can work online and offline, but remember two **important** things, the name of your [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) file must be `slides.md`. Also, your *local* images must be placed in a `images` folder at the same level that the `slides.md` file.

* For **online** working: Copy the URL of the `slides.md` file and paste it after:

  ```
http://datascienceseville.github.io/slides-viewer/viewer.html?md=
```

  If your `slides.md` file is hosted in GitHub use the raw URL and delete any parameters that it could have.

* For **offline** working: Download the `viewer.html` of this repo and place it at the same level that your `slides.md` file. But **caution**, the offline version only will work with Firefox.

Styles
------

The `viewer.html` file has the default CSS for the slides's style. You can take a look to the [oficial Remark's page](http://remarkjs.com/) for see this style in action. If you need some custom styles, please add it to the `style` tag of the `viewer.html` file. **But please**, don't overwrite the default HTML tag styles, add classes that don't make any conflict with any of the other classes.
