# slides-lectures

Some publicly available lecture slides, mainly from courses taught at
Université de Lorraine.

There's a mix of french and english slides.

ssh: Introduction to SSH (Taught in ASRALL, Outils Libres)

## Compiling

Installing build-dependencies:
* Texlive stuff:
 apt-get install --no-install-recommends texlive-latex-extra texlive-latex-recommended texlive-fonts-recommended texlive-fonts-extra
* Additional tools for building and translations:
 apt-get install --no-install-recommends latex-make po4a

To translate the document, po4a is used. You need to edit po4a/po/fr.po, and
run 'make translate' to translate the file and create (e.g.) ssh.fr.tex. Then
pdflatex ssh.fr.tex to generate the PDF, or just 'make ssh.fr.pdf'. There are
high-level tools and plugins for various editors to edit the po file.

Also look at
http://anonscm.debian.org/cgit/collab-maint/packaging-tutorial.git/tree/README.translators
(which uses the same toolset for translations)

## License 

This document (or aggregation of documents) is free software: you can
redistribute it and/or modify it under either (at your option):
- The terms of the GNU General Public License as published by the Free Software
  Foundation, either version 3 of the License, or (at your option) any later
  version.
  On Debian systems, the complete text of the GNU General
  Public License version 3 can be found in `/usr/share/common-licenses/GPL-3'.
  It can also be found on the web: http://www.gnu.org/licenses/gpl.html
- The terms of the Creative Commons Attribution-ShareAlike 3.0 Unported License,
  which can be found at http://creativecommons.org/licenses/by-sa/3.0/legalcode.
