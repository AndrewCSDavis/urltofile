# URL to File Type

The URL to File Type extension allows you to generate PDF/DOCX files for a whole or subset of your Symphony page.

## Installation

1. Upload the `urltofiletype` folder to your Symphony `/extensions` folder.
2. Enable it by selecting the "URL to File Type" from the Symphony extensions page, choose "Enable/Install" from the "With Selected..." menu, then click Apply.
3. You can now add the page type of `pdf` or `docx` to your pages

Usage

either by navigating to frontend page that has the pagetype attached to it you can either view it or by appending `?download=pdf` to the end of the url
you can receive a download in the form of the pdf from the actual page

there are other options such as 

`<a href="{$root}/page-name/?download=pdf">Download PDF</a>`

this also applies to the same of `docx` as the pagetype
