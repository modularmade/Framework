#Modular Made 1.0

Modular Made is a Object-Oriented framework for Sass 3.3 that combines OOCSS with Atoms.

**Features**

1. **Mobile-first**

	Objects use progressive enhancement to fit to larger screens.

2. **Abstraction-light**

	By using low-level utility classes called Atoms, abstractions are at a minimum.

	[Learn more](http://www.smashingmagazine.com/2013/10/21/challenging-css-best-practices-atomic-approach/)

3. **Extendable**

	Download or create your own themes.

##Browser Support

Modular Made was designed for modern browsers, including IE8 and above.

##Installation

Install using the command line:

    git clone --recursive git@github.com:modularmade/modularmade-web-template.git your-folder
    $ cd your-folder
    $ ./go

##Getting Started

Once you installed Modular Made, you should be looking at the following folder structure:

	sass/
		builds/
			_default.scss
		themes/
			_default.scss
		source/
		imports.scss

**Builds Folder**

The `build` folder contains a variable file (`_default.scss`) that determine which components to include: 

For example:

    $use-sect:  true;
    $use-grid:  true;
    $use-media:	true;

**Themes Folder**		

The `themes` folder contains a variable file (`_default.scss`) that determine which the branding rules:
  
For example:

	$sp-xs: 	6px;
	$sp-s: 		12px;
	$sp-m: 		24px;
	$sp-l: 		36px;
	$sp-xl: 	68px;

**Imports.scss**		

The `imports.scss` file contains pointers to the build and theme variable files.

	@imports 'builds/_default';
	@imports 'themes/_default';

##Customization

Feel free to create your own builds and themes by making a copy of their `_default.scss` file, and editing it.



