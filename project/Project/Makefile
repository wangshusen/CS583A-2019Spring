all: html pdf docx rtf

pdf: proj.pdf
proj.pdf: proj.md
	pandoc --standalone --template style_chmduquesne.tex \
	--from markdown --to context \
	-V papersize=A4 \
	-o proj.tex proj.md; \
	context proj.tex

html: proj.html
proj.html: style_chmduquesne.css proj.md
	pandoc --standalone -H style_chmduquesne.css \
        --from markdown --to html \
        -o proj.html proj.md

docx: proj.docx
proj.docx: proj.md
	pandoc -s -S proj.md -o proj.docx

rtf: proj.rtf
proj.rtf: proj.md
	pandoc -s -S proj.md -o proj.rtf

clean:
	rm proj.html
	rm proj.tex
	rm proj.tuc
	rm proj.log
	rm proj.pdf
	rm proj.docx
	rm proj.rtf
