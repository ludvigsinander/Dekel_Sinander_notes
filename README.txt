Files:
- ms.tex: main .tex file
- preamble.tex: subsidiary .tex file called by ms.tex
- bibl.bib: bibliographic repository, called by ms.tex
- ms.bbl: .bbl file, using Biber version 2.8
- COPYING.txt: license information.

To produce PDF lecture notes, compile ms.tex using pdfLaTeX. Run biber to create a new .bbl file.