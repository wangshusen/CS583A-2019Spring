all: html pdf docx rtf

pdf: HM.pdf
HM.pdf: HM.md
	pandoc --standalone --template style_chmduquesne.tex \
	--from markdown --to context \
	-V papersize=A4 \
	-o HM.tex HM.md; \
	context HM.tex

html: HM.html
HM.html: style_chmduquesne.css HM.md
	pandoc --standalone -H style_chmduquesne.css \
        --from markdown --to html \
        -o HM.html HM.md

docx: HM.docx
HM.docx: HM.md
	pandoc -s -S HM.md -o HM.docx

rtf: HM.rtf
HM.rtf: HM.md
	pandoc -s -S HM.md -o HM.rtf

clean:
	rm HM.html
	rm HM.tex
	rm HM.tuc
	rm HM.log
	rm HM.pdf
	rm HM.docx
	rm HM.rtf
