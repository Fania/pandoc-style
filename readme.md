# Pandoc custom templates

pandoc coursework-01.md -f markdown_mmd -o cw1.pdf --data-dir=C:\Users\Fania\Documents\GitHub\pandoc-style\ --template simple



## Anything to TeX

pandoc demo.md -s -o output.tex


## Markdown to HTML

https://wkhtmltopdf.org/

pandoc cheatsheet.md -f markdown_mmd -t html5 -o cheatsheet.html


## Web to Markdown

pandoc -f html -t markdown http://www.fsf.org -o test.md


## Options

--metadata-file=FILE
--template=FILE|URL

--include-in-header=FILE|URL
--include-before-body=FILE|URL
--include-after-body=FILE|URL


--toc
--toc-depth=NUMBER

--bibliography=FILE
--reference-links
--reference-location = block|section|document
--biblatex

--number-sections


--listings

--mathjax[=URL]




## ODT to DOCX/PDF


pandoc test.odt -o test.docx

pandoc test.odt -o test.pdf
