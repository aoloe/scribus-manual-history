# Notes

Release notes:

Announces:

-  [Open Source Desktop Publishing - Scribus 1.0 Released](http://www.graphics.com/news-old/open-source-desktop-publishing-scribus-10-released), 14.7.2003
- [Scribus 1.0 Released ](https://dot.kde.org/2003/07/18/scribus-10-released), 18.7.2003 on <http://dot.kde.org>

Reviews:

- [Review of SCRIBUS 1.0 - a Free DTP for UNIX](http://www.osnews.com/story/4064)

Articles:

- [Introducing Scribus](http://www.linuxjournal.com/article/7054), Nov 01, 2003  By Peter Linnell

## Release notes

<https://web.archive.org/web/20030724105726/http://home.comcast.net/~scribusdocs/>

Scribus 1.0 (Released 2003:07:14) - Major features from 0.9.x developer releases:

-  Numberous small bug fixes and refinements throughout. The most stable version released to date.
-  The SVG-Export plug-in is now part of the main distribution and it supports all objects in a Scribus doc. Images are saved as PNG.
-  Added New Plugin for Print Preview.
-  Added Support for Links to external PDF-Documents.
-  The first page of a PDF can now placed like a EPS-File.
-  Added new Command "Convert Text to Polygons" - Very cool..
-  Vastly Improved Text Rendering for at all Zoom Factors > 100 % with freetype2
-  Added Color Model "Websave RGB"
-  Added the possiblity to adjust the Display for true WYSIWYG. e.g 1 Inch displayed on the Rulers is now really an Inch on the Screen.
-  Support for Unicode fonts via freetype2. This allows both Unicode text and usage of all the glyphs within Unicode fonts. You need freetype2 to enable this feature.
-  Support for embedding icc profiles when printing directly from Scribus. This will allow for print proofs which simulate standard CMYK press conditions or well profiled printers.
-  Implemented Reverse Writing Mode for Textboxes. This enables right to left languages such as Hebrew and Arabic script.
-  Hungarian Hyphenation added
-  Improved the zooming with the Mouse Wheel by enableing it when you press the Mouse Wheel
-  A newly revised measurements palette with addtional functions and reduced screen usage.
-  You can now zoom In and out withe the Mouse Wheel when you hold the Shift-Key whilst rotating the Wheel.
-  The Postscript Driver can now separate RGB-Images too. The only thing that doesn't work are Gradient Fills of Objects on Template Pages.
-  The PDF-Exporter converts now RGB-Images to CMYK when Destination Printer is selected.
-  Added a command to save everything into a folder to ease moving files.
-  The first standalone application to create 100% PDF/X-3 compliant PDF's. This is a major advance in the capabilties for Scribus to produce "press-ready" PDF's suitable for use in commercial printing. Info and PDF/X-3 Q and A
-  Added support for CUPS and Gimp-Printfor high quality printing from inkjets and other printers supported by Gimp-Print.
-  Scribus can encrypt PDF's with 128 bit strength.
-  Embedding of ICC-Profiles in PDF's is now an option.
-  Support for PDF-1.4 Transparency. There is a check box in the preferences to enable it. By default it is off. ** Thus, PDF's created with this enabled will only show transparency in Acrobat Reader 5.0+ or the full version of Acrobat 5.0+ **
-  Reworked Font Preferences
-  Scribus installs now in $prefix/lib instead of $prefix/share to be compliant with the FHS.
-  Gradient Fills for all Objects except Pictures
-  Guidelines which can be dragged out of the Rulers
-  A locking function for objects - both graphic elements and text frames
-  A Button in the File Select or File Save As: which navigates to a preferred directory for saving your Scribus docs - defined in File -> Preferences. This works much like Star Office or Open Office, if you are familiar with these applications.
-  PDF Options are now saved with the Document
-  A much requested feature, MDI (mulitple document interface) is in Scribus. This give users the ability to have multiple Scribus Documents open, as well as copy paste/move objects between documents.

## Features

- By the way, this also shows off the MDI (Mutliple Document Interface) added in 0.9.x. In other words, you can have more than one Scribus doc open at the same time; a much requested feature.
- This is the new image modify panel. you can now apply names to object independent of the file name, as well as free scale images. 
- There is some important code in Scribus which is floating point math. The new compiler optimizations and enhanced floating point units in newer processors really speed up certain functions within Scribus.
- My (Peter? ndr) perception is about a 25%-50% speed increase when performing demanding tasks like creating large PDF's with hi-res tiffs