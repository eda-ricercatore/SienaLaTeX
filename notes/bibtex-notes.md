#	Important BibTeX Information That I Tend to Use


##	BibTeX Entry Types


+ ***@article***
	- Entry for an article from a journal or magazine.
	- required fields: author, title, journal, year.
	- optional fields: volume, number, pages, month, note, **DOI**.
+ ***@book***
	- Entry for a book with a definite publisher.
	- required fields: author or editor, title, publisher, year.
	- optional fields: volume or number, series, address, edition, month, note, **DOI**.
+ **@booklet**
	- Entry for a printed and bound work without the name of a publisher or sponsoring organization.
	- required fields: title.
	- optional fields: author, howpublished, address, month, year, note.
+ @conference
	- Is the same as @inproceedings below.
	- Deprecated. ***Do not use.***
+ ***@inbook***
	- Entry for a part (chapter, section, certain pages) of a book.
	- required fields: author or editor, title, chapter and/or pages, publisher, year, **DOI**.
	- optional fields: volume or number, series, type, address, edition, month, note.
	- Might not support these fields: crossref.
+ ***@incollection***
	- Entry for part of a book that has its own title.
	- required fields: author, title, **booktitle**, publisher, year.
	- optional fields: editor, volume or number, series, type, chapter, pages, address, edition, month, note, **DOI**.
	- Might not support these fields: crossref
+ ***@inproceedings***
	- Entry for an article in conference proceedings.
	- required fields: **author, title, booktitle, year, DOI**.
	- optional fields: **editor, volume or number, series, pages, address, month**, organization, **publisher**, note, crossref.
+ ***@manual***
	- Entry for technical documentation.
	- required fields: title.
	- optional fields: author, organization, address, edition, month, year, note.
+ ***@mastersthesis***
	- Entry for a Master's thesis.
	- required fields: author, title, school, year.
	- optional fields: type, address, month, note.
+ ***@misc***
	- Entry for a work that does not fit under any of the others.
	- required fields: none.
	- optional fields: author, title, howpublished, month, year, note, **URL**.
+ ***@phdthesis***
	- Entry for a PhD thesis.
	- required fields: author, title, school, year.
	- optional fields: type, address, month, note, **howpublished, URL**.
+ ***@proceedings***
	- Entry for conference proceedings.
	- required fields: title, year.
	- optional fields: editor, volume or number, series, address, month, organization, publisher, note, crossref.
+ ***@techreport***
	- Entry for a report published by a school or other institution, usually as part of a series.
	- required fields: author, title, institution, year.
	- optional fields: type, number, address, month, note, **howpublished**.
	- Might have to add the following fields: publisher.
+ **@unpublished**
	- Entry for an unpublished work with an author and title.
	- required fields: author, title, note.
	- optional fields: month, year.
+ **@electronic**
	- Used by IEEE Press.
	- Only for IEEE publications, such as CDs, DVDs, and Web pages.
	- fields:
		* address
		* author
		* howpublished  ("Available online from BLAH at: URL; DATE was the last accessed date")
		* note
		* organization
		* pages
		* title
		* year














##	BibTeX Fields


+ address
	- The address of the publisher or other institution. For major publishing houses, it is sufficient to give just the city. For smaller publishers, giving the full address is recommended.
+ annote
	- An annotation that may be used by **non-standard bibliography styles** to produce an **annotated bibliography**. The standard BibTeX styles ignore it.
+ author
	- The name(s) of the author(s) as described in Section 14.2.4.
+ booktitle
	- The title of a book when only part of it is being cited. See Section 14.2.4 for special considerations on capitalization.
+ chapter
	- A chapter or section number.
+ crossref
	- The key of another entry in the database that shares many of the same field entries. See Section 12.2.3.

[comment]: <> (14.2.3 in the PDF copy.)

	- Used for the BibTeX entry type **inproceedings**.
	- Try to see if this would work for the BibTeX entry types **incollection** and **inbook**.
+ edition
	- The edition of a book, usually written in full and capitalized, as ‘Second’. The standard styles will change it to lower case as necessary.
+ editor
	- The name(s) of the editor(s) as described in Section 14.2.4. If there is also an author field, then this gives the editor of the book or collection in which the citation appears.
+ howpublished
	- States anything unusual about the method of publishing. Should be capitalized. Example: ‘Privately published’.
+ institution
	- The name of the sponsoring institution for a **technical report**.
+ journal
	- The name of a journal or magazine. Abbreviations are provided for the most common ones (see Section 14.2.5).
+ key
	- An addition for alphabetizing purposes when the author infor- mation is missing. This is not the same as the key for identifying the entry to a \cite command.
+ month
	- The month in which the work was published or, if unpublished, when it was written. Abbreviations exist in the form of the first three letters of the (English) names.
+ note
	- Any additional information that should be added. Capitalize the first letter.
+ number
	- The number of a journal, magazine, technical report, or work in a series. Journals are usually identified by volume and number; technical reports are issued a number by the institution; books in series sometimes have a number given to them.
+ organization
	- The sponsoring organization for a **conference or a manual**.
+ pages
	- A page number or a range of pages, in the form 32,41,58 or 87--101 or 68+. The last form indicates page 68 and following pages. A single hyphen given for a range will be converted by the standard styles to the double hyphen to produce a dash, as ‘87–101’.
+ publisher
	- The publisher’s name.
+ school
	- The name of the academic institution where a thesis was written.
+ series
	- The name of a series or set of books. When citing a book from a series, the title field gives the name of the book itself while the optional series specifies the title of whole set.
+ title
	- The title of the work, obeying the capitalization rules listed in Section 14.2.4.
+ type
	- The type of technical report, for example, ‘Research Note’.
+ url
	- The universal resource locator, or Internet address, for online documents; this is not standard but supplied by more modern bibliography styles.
+ volume
	- The volume number of a journal or multi-volume book.
+ year
	- The year in which the work was published or, if unpublished, in which it was written. It should normally consist of four numerals, such as 1993.
+ Additional field names may be included, which BibTeX will simply ignore. For example, to add the abstract of an article in the database,
	- abstract = {text of an abstract}





##	Lists, Summary Tables, and Figures of Interest


Lists, summary tables, and figures of interest:
+ From \cite{Kopka2004}:
	- \S12.2.1, pages 230-231 provides a list of BibTeX entry types.
	- \S12.2.2, pages 232-233 provides a list of BibTeX fields.
	- From Appendix G, Tables G.1-G.26 (especially Tables G.1-G.18, pages 547-550) in Section G.2, pages 547-553.

[comment]: <> (From PDF copy of \cite{Kopka2004}, Tables H.1-H.26 in Section H.2, pages 595-601.)












##	Notes

###	Using **crossref**

Use **crossref** for BibTeX entries using the BibTeX entry type **inproceedings** to share information about the conference proceedings without having to copy and paste fields that are commonly shared by articles/papers in conference proceedings [Carter2017] \cite[\S12.2.3, pp. 234]{Kopka2004}. It might not work with BibTeX entry types **inbook** and **incollection** for parts, subsections, sections, and chapters of books; this is not mentioned, and **crossref** is probably not supported for these BibTeX entry types.




Code snippet from [Carter2017].

	@inproceedings{duck2015,
		author = {Duck, D.},
		title = {Duck tales},
		crossref = {ICRC2015},
	}

	@inproceedings{mouse2015,
		author = {Mouse, M.},
		title = {Mouse stories},
		crossref = {ICRC2015},
	}

	@proceedings{ICRC2015,
		title = "{Proceedings of the 34\textsuperscript{th} International Cosmic Ray Conference}",
		year = "2015",
		month = aug,
	}






From [valerie2017], the appearance of the "References" section/list can vary between different LaTeX styles (i.e., formats) and customized bibliographic styles (from customized bibliographic style files [WikipediaContributors2020]). Hence, instead of changing my BibTeX database, fix copies of my BibTeX database.
+ *bib2bib* is a tool that "provides pretty flexible and reliable ways to filter/extract/expand BibTeX entries" [Daniel2011]
	- "This (little known) utility is part of the bibtex2html tool suite."
	- "Note: you have to look for the PDF documentation, the HTML documentation does not discuss bib2bib!"
	- This is suggested by [Daniel2017].
+ Use the **crossref** field each each specific peer-reviewed, co-authored document by my co-authors and myself
	- We have to compromise or decide as a team whether to use the **crossref** field.
















**References**:
+ [Carter2017] Sam "samcarter" Carter, Answer to "What is the Bibtex crossref field used for?," Stack Exchange Inc., New York, NY, November 13, 2017. Available online from {\it Stack Exchange Inc.: Stack Overflow: Questions} at: https://tex.stackexchange.com/questions/401138/what-is-the-bibtex-crossref-field-used-for and https://tex.stackexchange.com/a/401142/201705; December 1, 2020 was the last accessed date.
+ [valerie2017] valerie, Thomas "lockstep" Titz, and Daniel, "when multiple entries crossref the same proceeding, the proceeding details are not printed, but cited!", Stack Exchange Inc., New York, NY, April 13, 2017. Available online from {\it Stack Exchange Inc.: Stack Overflow: Questions} at: https://tex.stackexchange.com/questions/256227/when-multiple-entries-crossref-the-same-proceeding-the-proceeding-details-are-n and https://tex.stackexchange.com/q/256227/201705; December 1, 2020 was the last accessed date.
+ [WikipediaContributors2020] Wikipedia contributors, "BibTeX," in *Wikipedia, The Free Encyclopedia: Bibliography file formats*, Wikimedia Foundation, San Francisco, CA, November 25, 2020. Available online at: https://en.wikipedia.org/wiki/BibTeX; last accessed on December 10, 2020.
+ [Daniel2011] Daniel, Answer to "Flattening BibTeX files," Stack Exchange Inc., New York, NY, October 13, 2011. Available online from *Stack Exchange Inc.: Stack Overflow: Questions* at: https://tex.stackexchange.com/questions/31380/flattening-bibtex-files/31381#31381 and https://tex.stackexchange.com/a/31381/201705; December 1, 2020 was the last accessed date.
+ [Daniel2017] Daniel and Community Stack Exchange bot, Answer to "when multiple entries crossref the same proceeding, the proceeding details are not printed, but cited!", Stack Exchange Inc., New York, NY, April 13, 2017. Available online from {\it Stack Exchange Inc.: TeX - LaTeX Community: Questions} at: https://tex.stackexchange.com/questions/256227/when-multiple-entries-crossref-the-same-proceeding-the-proceeding-details-are-n and https://tex.stackexchange.com/q/256227/201705; December 1, 2020 was the last accessed date.







