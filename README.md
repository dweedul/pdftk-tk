# pdftk-tk

This is a small set of bash scripts and windows batch files used for making pdftk just a little easier to use.

## Installing
 1. Download [pdftk]
 1. Clone the repo
 1. Ensure that pdftk is accessible to the scripts via the $PATH or some other smart way of doing that.

## Informational Scripts

__num-pages__
echos the number of pages in the batch file.  This is a dependency for many of the other scripts
    num-pages <pdfname>

## PDF manipulation

__make-signatures__
makes signatures from a given pdf.
    make-sigs <filename> [pages-per-signature]

## Windows Batch Files

These allow for drag-and-drop operations in Windows
  * burst_pdf.cmd
  * rotate_pdf_90deg_ccw.cmd
  * rotate_pdf_90deg_cw.cmd


[pdftk]: http://www.pdflabs.com/tools/pdftk-the-pdf-toolkit/