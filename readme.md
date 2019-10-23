# Pandoc custom templates

pandoc coursework-01.md -f markdown_mmd -o cw1.pdf --data-dir=C:\Users\Fania\Documents\GitHub\pandoc-style\ --template simple



## Anything to TeX

pandoc demo.md -s -o output.tex


## Web to Markdown

pandoc -f html -t markdown http://www.fsf.org -o test.md