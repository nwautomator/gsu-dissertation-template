# README #

This repository provides an easy to use, templatized Ph.D. dissertation in LaTeX format. It was primary created for use by graduate students at [Georgia State University](http://www.gsu.edu/), but can be easily edited for your own use.

## Setup ##
In order to use this template, you should have a [LaTeX](http://www.latex-project.org/) distribution installed and working. Many exist, depending on the particular platform you're using. In general:

* [TeX Live](http://www.tug.org/texlive) - Install TeX Live if you're on a Unix or Unix-like operating system such as Linux.
* [MacTeX](http://www.tug.org/mactex/) - Install MacTeX if you're on a Macintosh system.
* [proTeXt](http://www.tug.org/protext/) - Install proTeXt if you're on a Windows system.

Installing any of the above should provide you with the vast majority of additional LaTeX packages, but it's possible that you may need to install the 'science' package if you're using TeX Live. This package is usually named `texlive-science` under most systems.

### Customizing The Template ###
You'll find a few subdirectories under the main template repository. These are used as follows:

* `boiler` - All "boilerplate" text, needed to customize the template to your specific use case. The following changes should be made:
 * `boiler/abstract.tex` - Write the contents of your abstract here, where the commented line is located.
 * `boiler/abbreviations.tex` - Add any abbreviations for acronyms here.
 * `boiler/acknowledgement_page.tex` - Write the contents of your acknowledgements here.
 * `boiler/advisor.tex` - Change this to the name of the professor that is advising your graduate work.
 * `boiler/approval.tex` - Change this to reflect the name of the office, unit, school, or college that approved your paper.
 * `boiler/author.tex` - Change this to your name.
 * `boiler/committee.tex` - Change this to reflect the names of the members of your graduate committee.
 * `boiler/dedication_page.tex` - Write the contents of your dedication(s) here.
 * `boiler/degree.tex` - Change this to reflect the name of the degree to which you are working.
 * `boiler/keywords.tex` - Change this to reflect any keywords (or phrases) that your paper should be indexed by for searching.
 * `boiler/title.tex` - Change this to what you'd like the title of your paper to be.
* `chapters` - All text that is part of your actual graduate thesis or dissertation. The files here can be renamed to your liking as long as you change the `main.tex` file at the root of the repository to reflect your changes. You can even add additional chapters if needed; simply create the new files and reference them in `main.tex`.
* `packages` - This directory contains a few style files needed to generate a nice looking paper. There should be no need to edit any files under this directory.
