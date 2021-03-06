Converts .doc, .docx and .pdf files to PNG.

Features
========
* Multi-page document support
* Windows/File Explorer integration

Prerequisites
=============
* Operating system: Windows XP or later
* Python 2.7 or 3.1, available [here](http://www.python.org/getit/). Note that Python 3.1 is
  required to support Unicode file names.
* comtypes, available [here](http://sourceforge.net/projects/comtypes/files/comtypes/)
* Ghostscript, available [here](http://www.ghostscript.com/download/gsdnld.html)
* ImageMagick, available [here](http://www.imagemagick.org/script/binary-releases.php#windows)
* Optional: Microsoft Word (required to support conversion of Word documents)

Building a Windows installer
============================
`$ python setup.py bdist_wininst --install-script=postinstall.py`

Usage
=====
In File Explorer
----------------------
Right-click the Word Document and select 'Convert to PNG'.

From the command line
---------------------
`$ python document2image.py <document>`
