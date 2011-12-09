# pdftk-tk

This is a small set of bash scripts and windows batch files used for making pdftk just a little easier to use.

## Installing

 1. Download [pdftk]
 1. Clone the repo
 1. Ensure that pdftk is accessible to the scripts via the $PATH or some other smart way of doing that.

## Informational Scripts

__num-pages__

Returns the number of pages in the pdf.  This is a dependency for many of the other scripts

    num-pages <pdfname>

## PDF manipulation

__build-pad__

Repeats a pdf to some number of pages.  Useful for making pads of blank or ruled paper.

    build-pad <pdf filename> <number of pages> [output filename]

__make-signatures__

Makes signatures from a given pdf.

    make-sigs <filename> [pages-per-signature]

## Windows Batch Files

These allow for drag-and-drop operations in Windows

  * burst_pdf.cmd
  * rotate_pdf_90deg_ccw.cmd
  * rotate_pdf_90deg_cw.cmd


[pdftk]: http://www.pdflabs.com/tools/pdftk-the-pdf-toolkit/