slides.html: slides.md
	pandoc -s -t slidy slides.md -o slides.html

install: slides.html
	mkdir -p ${out}/share/domcode-slides
	cp slides.html ${out}/share/domcode-slides/


