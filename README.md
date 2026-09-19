This repository contains a LaTeX template for Ohio State dissertations. Due to Ohio State's relatively new [Accessibility Policy](https://it.osu.edu/das), dissertations need to meet these accessibility standards:

* PDF file includes full text
* PDF accessibility permission flag is checked
* Text language of the PDF is specified
* PDF includes a title
* Images, figures, and tables have descriptive captions and/or alt tags explaining content

Some of these requirements don't play well with some widely used LaTeX dissertation templates, such as the one from [Jon Dehdari](https://jon.dehdari.org/latex/osuthesis/) on which this repository is based. And reformatting a completed but non-accessible dissertation to be accessible can be massive headache (as I learned from unfortunate personal experience). Hopefully starting with this template can reduce the pain.

To future dissertators: if you find that this template doesn't comform to future accessibility standards or doesn't meet your needs in other ways, please send in a pull request so that it continues to be a useful resource!

## Notes
* This template is designed for LuaLaTeX. Older engines like pdfLaTeX are pretty horrible at tagging for accessibility. Make sure you've downloaded a current version of LuaLaTeX (or selected it on Overleaf) before trying to compile.
* Anecdotally, missing alt text for images and figures has been a main reason why LaTeX-based dissertations have not passed OSU's [Format Review](https://gradsch.osu.edu/current-students/dissertations-and-theses/format-review-and-submission). See chap.foo.tex for an example of how to add alt text
* Adobe Acrobat has built-in tools you can use to verify that your final PDF is accessible.

## Resources and References
* [Jon Dehdari's template](https://jon.dehdari.org/latex/osuthesis/)
* [Info about OSU format reviews](https://gradsch.osu.edu/current-students/dissertations-and-theses/format-review-and-submission)
* [OSU Digital Accessibility Guide](https://gradsch.osu.edu/current-students/dissertations-and-theses/document-preparation/digital-accessibility-guide)
