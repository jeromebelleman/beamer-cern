I found [Beamer](https://bitbucket.org/rivanvx/beamer) to be
rather popular at CERN and it's certainly the only decent way of
making slides  I've found in recent years (in all fairness, the
[Sozi](http://sozi.baierouge.fr)/[Inkscape](http://www.inkscape.org)
pair isn't bad at all either). So I thought I'd write
a Beamer theme following the official [CERN design
guidelines](http://design-guidelines.web.cern.ch/presentations).

# Documentation and Sample Presentation

[beamer-cern.pdf](beamer-cern.pdf):

<a href="images/beamer-cern-00.png"><img src="thumbnails/beamer-cern-00.png" height="64" /></a>
<a href="images/beamer-cern-01.png"><img src="thumbnails/beamer-cern-01.png" height="64" /></a>
<a href="images/beamer-cern-02.png"><img src="thumbnails/beamer-cern-02.png" height="64" /></a>
<a href="images/beamer-cern-03.png"><img src="thumbnails/beamer-cern-03.png" height="64" /></a>
<a href="images/beamer-cern-04.png"><img src="thumbnails/beamer-cern-04.png" height="64" /></a>
<a href="images/beamer-cern-05.png"><img src="thumbnails/beamer-cern-05.png" height="64" /></a>
<a href="images/beamer-cern-06.png"><img src="thumbnails/beamer-cern-06.png" height="64" /></a>
<a href="images/beamer-cern-07.png"><img src="thumbnails/beamer-cern-07.png" height="64" /></a>
<a href="images/beamer-cern-08.png"><img src="thumbnails/beamer-cern-08.png" height="64" /></a>
<a href="images/beamer-cern-09.png"><img src="thumbnails/beamer-cern-09.png" height="64" /></a>
<a href="images/beamer-cern-10.png"><img src="thumbnails/beamer-cern-10.png" height="64" /></a>
<a href="images/beamer-cern-11.png"><img src="thumbnails/beamer-cern-11.png" height="64" /></a>
<a href="images/beamer-cern-12.png"><img src="thumbnails/beamer-cern-12.png" height="64" /></a>
<a href="images/beamer-cern-13.png"><img src="thumbnails/beamer-cern-13.png" height="64" /></a>
<a href="images/beamer-cern-14.png"><img src="thumbnails/beamer-cern-14.png" height="64" /></a>
<a href="images/beamer-cern-15.png"><img src="thumbnails/beamer-cern-15.png" height="64" /></a>
<a href="images/beamer-cern-16.png"><img src="thumbnails/beamer-cern-16.png" height="64" /></a>
<a href="images/beamer-cern-17.png"><img src="thumbnails/beamer-cern-17.png" height="64" /></a>

# Installation

Copy the files to `~/.texmf`, `/usr/share/texlive/texmf-dist` (if you use
Tex Live), `/usr/share/texmf` or something similar.

# The CERN Logo

It's not provided here but there are official [CERN logos available for
download](https://design-guidelines.web.cern.ch/downloads).
Download the [*CERN logo
pack*](https://design-guidelines.web.cern.ch/sites/design-guidelines.web.cern.ch/files/downloads/CERN-LogoPack.zip).

A quick and dirty way to include a suitable logo is to copy the
`CERN-LogoPack/Outline/PNG/WHITE/LogoOutline-04.png` file to the directory
where your slides are. Rename it to `cern-logo.png`.

A cleaner way would involve using a vector graphics editor such as
[Inkscape](https://inkscape.org) and editing the `CERN-LogoPack/Outline/Format
PAO/LogoOutline.svg` file to turn the logo outline white. Then export it as a
PDF file to the directory where your slides are. Rename it to `cern-logo.pdf`.
