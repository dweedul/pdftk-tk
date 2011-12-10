# pdftk-tk

This is a small set of bash scripts and windows batch files used for making pdftk just a little easier to use.

## Installing

 1. Download [pdftk]
 1. Clone the repo
 1. Ensure that pdftk is accessible to the scripts via the $PATH or some other smart way of doing that.

## Informational Scripts

__count-pages__

Returns the number of pages in the pdf.  This is a dependency for many of the other scripts

    count-pages <pdfname>

## PDF manipulation

__build-pad__

Repeats a pdf to some number of pages.  Useful for making pads of blank or ruled paper.

    build-pad <pdf filename> <number of pages> [output filename]

__signature-split__

Splits a given pdf into signatures for binding

    make-sigs <filename> [options]

    options:
    --sheets   : number of sheets per signature, defaults to 6
    --filespec : the format for the output filename in printf formatting

## Windows Batch Files

These allow for drag-and-drop operations in Windows

  * burst_pdf.cmd
  * rotate_pdf_90deg_ccw.cmd
  * rotate_pdf_90deg_cw.cmd


[pdftk]: http://www.pdflabs.com/tools/pdftk-the-pdf-toolkit/