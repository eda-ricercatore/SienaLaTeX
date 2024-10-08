#	SienaLaTeX


A repository for my *LaTeX* templates.

This contains templates for *LaTeX* documents that I tend to create, *LaTeX* structures that I tend to use (such as tables, lists, and figures), and *LaTeX* commands.



This repository is organized as follows:  
1)	Documents for this projects that are in the text file format. E.g., [LICENSE.md](https://github.com/eda-ricercatore/SienaLaTeX/blob/master/LICENSE.md) and [README.md.](https://github.com/eda-ricercatore/SienaLaTeX/blob/master/README.md)  
2)	articles: A *LaTeX* template for articles.  
3)	curriculum_vitae: A *LaTeX* template for curriculum vitaes and resumes.  
4)	presentations: A *LaTeX* template for creating presentation slides.  
5)	reports: A *LaTeX* template for reports.  
6)	scripts: A *Ruby* script to remove temporary files, and *Python* scripts to
		manage *BibTeX* databases.
7)	[notes](https://github.com/eda-ricercatore/SienaLaTeX/blob/master/notes/latex.md): Notes that I have written to remind me of certain commonly used *LaTeX* features by myself.

For each subdirectory, a *Makefile* is provided to typeset the document with *LaTeX* (and add references, if necessary).

Use the *Makefile* to typeset the *LaTeX* document.

>	## ⚠️ WARNING: Makefile problems with different LaTeX engines.
>	Some LaTeX engines don't have a lot of LaTeX packages installed.
>	Using *pdflatex* to typeset LaTeX documents may produce errors,
>		if LaTeX packages that are used in the template are not installed.

To do that, try the following on the command line of a *UNIX*-like operating system: make latex

For the *LaTeX* templates for articles and reports, they use *LaTeX* packages that may not be available in some *LaTeX* engines. For *LaTeX* engines without lots of installed packages,  try the following on the command line of a *UNIX*-like operating system: make simple

If the *LaTeX* typesetting system is not installed on your computer, you can download it for free from either of the following:
* [LaTeX -- A document preparation system](http://www.latex-project.org/)
* [TeX Live](http://www.tug.org/texlive/)
* [MacTeX](http://www.tug.org/mactex/)
* [TeX Users Group (TUG)](http://tug.org/)
* [Com­pre­hen­sive TeX Archive Net­work (CTAN)](http://www.ctan.org/)


##	*LaTeX* Notes

[Zhiyang Ong's *LaTeX* Notes](https://github.com/eda-ricercatore/SienaLaTeX/blob/master/notes/latex.md)

###	Additional Comments

In *Markdown*, you can use *LaTeX* to typeset mathematical equations, such as Maxwell-Faraday equation (Faraday's law of induction): <p align="center"><img src="/tex/fae8bb729ecf9e6c89d9eca2c87ef597.svg?invert_in_darkmode&sanitize=true" align=middle width=210.47583314999997pt height=40.39034175pt/></p>

For *GitHub* users, they can use the *GitHub* App
	[TeXify](https://github.com/apps/texify) to transform *LaTeX* expressions
	in **\*.tex.md** files, and render their *LaTeX* expressions as embedded
	SVG images in the transformed *Markdown* documents.
This requires write access to (a specified subset of) your repositories,
	so that it can update your repositories with the transformed
	*Markdown* documents and SVG files.
It also takes a short delay to transform *Markdown* documents, and write the
	updates to your repositories.
The SVG picture files are located in the *tex* subdirectory of your
	repositories.
Note that the transformed *Markdown* documents contain embedded *HTML* code,
	which cannot be automatically transformed into a web page using *GitHub*'s
	automatic *Markdown* to *HTML* transformation;
	e.g., see the project web page of [*SienaLaTeX*](https://eda-ricercatore.github.io/SienaLaTeX/).
Hence, such automatically transformed web pages contain *HTML* code snippets
	that have been embedded into the *HTML*-based web pages.



##	Resources Added By Others

+ [Instructions for using *TeXlipse*, which supports *LaTeX* for the *Eclipse* integrated development environment (IDE)](https://github.com/eda-ricercatore/SienaLaTeX/tree/master/instruction_for_texlipse)
+ [Dr. Amir Sohrabi's introduction to *LaTeX*](https://github.com/eda-ricercatore/SienaLaTeX/tree/master/latex_introduction_to)









#	Author Information

The MIT License (MIT)

Copyright (c) <2016> Zhiyang Ong

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Email address: echo "cukj -wb- 23wU4X5M589 TROJANS cqkH wiuz2y 0f Mw Stanford" | awk '{ sub("23wU4X5M589","F.d_c_b. ") sub("Stanford","d0mA1n"); print $5, $2, $8; print " "; for (i=1; i<=1; i++) print "6\b"; print $9, $7, $6 }' | sed y/kqcbuHwM62z/gnotrzadqmC/ | tr 'q' ' ' | tr -d "\n" | tr -d 'ir' | tr y "\n"

Don't compromise my computing accounts. You have been warned.
