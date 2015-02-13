
#What is Science?

Science is an object-oriented CSS framework built on best-practice. It supports all modern browsers and IE 8+.

1. **Mobile-first**

	Science uses progressive enhancement to adjust to larger screens.

2. **Abstraction-light**

	Science uses Atoms to keep the amount of abstractions to a minimum.

	[Learn More](http://www.smashingmagazine.com/2013/10/21/challenging-css-best-practices-atomic-approach/)

3. **Extendable**

	Science allows developers to add their own themes and plugins.

#Installing

git clone `https://github.com/modularmade/science.css.git`

#Requirements

* Sass 3.3

#Structure

**Build Folder**

The `build` folder contains variables files that determine which components to include. 

	sass
		builds
			_default.scss

**Theme Folder**

The `theme` folder contains variables files that determine the brand, such as colors.

	sass
		themes
			_default.scss			
			
**Plugin Folder**

The `plugins` folder is where you can add additional plugins.

	sass
		plugins
			
**imports.scss**

The `imports.scss` file contains the location to builds, themes, and plugins.

	@import "builds/_default";
	@import "themes/_default";

#Copyright and License

Code and documentation copyright 2015-2016 Eric Harms. Code released under the MIT license. Docs released under Creative Commons.
