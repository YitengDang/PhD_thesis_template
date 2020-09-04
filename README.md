# PhD thesis latex template
Latex template for PhD thesis, based on the template from TU Delft ([TU Delft website](https://www.tudelft.nl/en/tu-delft-corporate-design/downloads/), [Overleaf](https://www.overleaf.com/latex/templates/template-for-tu-delft-reports-slash-theses/ppbxdkxcqxdz)). 

Changes from the original TU Delft template include:
* Bibliography. The template uses BibTeX for referencing (here is a [BibTeX tutorial](https://www.overleaf.com/learn/latex/Bibliography_management_with_bibtex)), instead of natbib. First create a .bib file (straightforward using refence software such as EndNote), then simply link the .bib file to the template. There is no need to manually input references this way. The default referencing style is set to the APS style (for physics papers), but can be edited in the class file (change the `style=phys` command; see [BibTeX bibliography styles](https://www.overleaf.com/learn/latex/Bibtex_bibliography_styles)).
* Fonts and colors. The modified template no longer uses the corporate colors of TU Delft, but replaces most in-text colors by black (this includes titles and headings). The default font for the template is [KP-fonts](https://www.ctan.org/pkg/kpfonts) instead of TU Delft corporate fonts, with Latin Modern (the default LateX font) as a fallback. 
* List of Figures. By default, includes a list of figures at the end of the thesis.
* Images. The template shows two examples of how to deal with large images, for which the captions no longer fit on the same page. 
* Class file comments. The class file has been heavily commented to make it easier to adjust layout by yourself.

To make use of the template, simply download the entire repository. The master file to run is "dissertation.tex". It links to the subfiles in the various subfolders. To edit the layout, edit the "dissertation.cls" file. Bibliography is done using the "dissertation.bib" file.
