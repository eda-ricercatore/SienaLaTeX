#	Notes About *LaTeX*


This is my notes about *LaTeX*.



##	Typesetting Issues

When I include a *BibTeX* database/file for using *BibTeX* with *LaTeX*, I can
	either use absolute/full paths or relative paths;
	that said, I am not allowed to use the shortcut to redirect a path from my
		home directory.



###	Use of Greek Letters

Greek letters can by typeset with the *LaTeX* "Math mode". Usage of Greek letters with diacritics (or diacritical marks, or accents) need to use *LaTeX* commands for diacritics in the *LaTeX* "Math mode", rather than *LaTeX* commands for diacritics in the *LaTeX* "Text mode" \cite{Pakin2008,Kopka2004}.




###	In-Text Citations

For in-text citations, use:
+ **\cite{BibTeXkey}** for citing BibTeX entries in my BibTeX database.
+ **\ref{LABEL}** to cross-reference \cite[\S11.2.1-\S11.2.2, pp. 211-212]{Kopka2004} a section, subsection, subsubsection, figure, table, or equation that is labeled with **\label{LABEL}**.






### Common Colors and Fonts that I Use

Colors and fonts that I use.
+ red
+ blue
+ magenta
+ bold (font)
+ cyan





###	Common Terms/Symbols that I Get Confused About 



+ DPLL: Davis-Putnam-Logemann-Loveland procedure
+ rules of inference
+ rules of deduction
+ stochastic local search



Table of common symbols for mathematical logic

| Symbol Name | Symbol  |
|-------------|---------|
| entails	  | \models |
| infers/proves/concludes | \vdash |
| implies	  | \Rightarrow, or \Longrightarrow |
| conjunction | \land or \bigwedge |
| disjunction | \lor or \bigvee |




Examples:
+ p \rightarrow q : 

A\lor B is true if {\displaystyle A} is true, or if {\displaystyle B} is true, or if both {\displaystyle A} and {\displaystyle B} are true.
A\land B 




###	Common Typesetting Errors


From \cite{Anderson2012}, the following error is encountered when extremely long lines (>= 200,000 characters long) exist in the LaTeX source document.

	Unable to read an entire line---bufsize=200000.
	Please increase buf_size in texmf.cnf.


Attempted solutions to resolve this:
+ Find my [texmf.cnf](/usr/local/texlive/2021/texmf.cnf) file, and increase the value of the bufsize variable \cite{Anderson2012}; `bufsize=9999999`.
	- This did not work for me, probably because the new assigned valued is too large.
		Or, 200000 is already too large to be supported by the LaTeX/BibTeX software workflow.




##	Date and Time Formats

If necessary, use \cite{Harders2010} to modify the date and time format.











## BibTeX Notes

See https://github.com/eda-ricercatore/SienaLaTeX/blob/master/notes/bibtex-notes.md for my *BibTeX* notes.








#	References

Citations/References that use the *LaTeX/BibTeX* notation are taken
	from my *BibTeX* database (set of *BibTeX* entries).


If these citations/references are not found in this list of references,
	information about them can be found in my BibTeX database.
+ BLAH...




##	Resources/References on the World Wide Web

Web pages for help in *LaTeX*:
+ Templates for optimization, or mathematical programming
	- [LaTeX Templates for Optimization Models](http://www.orcomplete.com/computer/sertalpbilal/latex-templates-for-optimization-models)
	- \cite{Cay2013}
	- [My implementation](https://github.com/eda-ricercatore/SienaLaTeX/blob/master/notes/examples/optimization_templates.pdf)
		* [*LaTeX* source file for my implementation](https://github.com/eda-ricercatore/SienaLaTeX/blob/master/notes/examples/optimization_templates.tex)
	- [Suggested implementation from John Hammersley, who provided the LaTeX document](https://github.com/eda-ricercatore/SienaLaTeX/blob/master/notes/examples/from-other-peeps/optimization-templates/main.tex)
		- I modified the author list to reflect this.
		- John Hammersley incorporated a suggestion from Vince Knight for typesetting mathematical optimization models in *LaTeX*.



##	References from My BibTeX Database



	@misc{Harders2010,
		Address = {Heidelberg, Germany},
		Author = {Harald Harders},
		Howpublished = {Available online from {\it Comprehensive {\TeX}\ Archive Network: Packages} as Version 2.28 at: \url{https://www.ctan.org/pkg/isodate}; May 29, 2021 was the last accessed date},
		Keywords = {LaTeX packages, LaTeX packages - date & time processing},
		Month = {January 3},
		Publisher = {Comprehensive {\TeX}\ Archive Network},
		Title = {isodate -- Tune the output format of dates according to language},
		Url = {https://www.ctan.org/pkg/isodate},
		Year = {2010}}






##	Textual Cache

###	Publishers and Addresses that I Commonly Encounter


Publishers and addresses that I commonly encounter:
+ IEEE Press: Piscataway, NJ.
+ IEEE Computer Society Press: Los Alamitos, CA.
+ ACM Press: New York, NY.










#	Author Information

The MIT License (MIT)

Copyright (c) <2016> Zhiyang Ong

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Email address: echo "cukj -wb- 23wU4X5M589 TROJANS cqkH wiuz2y 0f Mw Stanford" | awk '{ sub("23wU4X5M589","F.d_c_b. ") sub("Stanford","d0mA1n"); print $5, $2, $8; for (i=1; i<=1; i++) print "6\b"; print $9, $7, $6 }' | sed y/kqcbuHwM62z/gnotrzadqmC/ | tr 'q' ' ' | tr -d [:cntrl:] | tr -d 'ir' | tr y "\n"		Don't compromise my computing accounts. You have been warned.
