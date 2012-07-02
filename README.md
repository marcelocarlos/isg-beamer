ISG Beamer Themes
==========

Description
-----------
A set of beamer themes to be used by ISG staff and Students to create their presentations


Installation
------------
This theme can be used locally (in your project's folder only) or installed to be available system-wide.

### Local Installation

1) Extract the package isg-themes-x.x.x.zip to your projects folder

2) Select the theme by using the "usepackage" command. You can find more details and examples in the file example.tex

### System-wide Installation

1) Extract the package isg-themes-x.x.x.zip to (please note that the paths might change under different distributions and OS versions.):

> OS X: /usr/local/texlive/2011/texmf-dist/tex/latex/beamer/
> Linux: /usr/local/share/texmf/tex/latex/beamer
> Windows: C:\localtexmf\texmf\tex\latex\beamer

2) Update latex' filename database:

> Linux/OS X: open a terminal window and type "sudo texhash" to update the latex filename database. 
> Windows: open programs menu, MiKTeX 2.X, Maintenance (Admin), Settings (Admin). Under the "General" tab, click "Refresh FNDB".

3) Select the theme by using the "usetheme" command. You can find more details and examples in the file example.tex

Changelog
---------
#### Version 1.1.0 (23/02/2012) 
 * New folders structure
 * It can be now installed locally (inside a project) or system-wide
 * ISG logo on frames can be enabled/disabled by using parameters (displaylogo or nologo)
 * Slide's footer can be enabled/disabled by using parameters (displayfooter or nofooter)
 * An option to display the TOC in the beginning of every section can be enabled/disabled by using parameters (displaytocsection or notocsection)
 * An option to display the TOC in the beginning of every subsection can be enabled/disabled by using parameters (displaytocsubsection or notocsubsection)
 * Improvements on the document structure
 * Minor fixes

#### Version 1.0.0 (05/11/2009) 
 * First public  version
