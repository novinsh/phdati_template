# ATI Doctoral Thesis Template Package

The package contains template files for PhD students writing their doctoral thesis.
	
### Contents

- phdati.cls: A LaTeX class file for both monograph and collection of publications type of theses;
- phdstyle.sty: A LaTeX style file for both monograph and collection of publications type of theses;
- main.tex: The main file for the LaTeX template with the thesis details need to be filled here;
- bibliography.bib: A Latex file for the bibliography 
- sections/: directory to keep the content of thesis in, children files reflect the main document structure 
- figures/: to store the figures for the document

### Things that should not be changed

You should not change:

- The text area size, as well as horizontal and vertical margins;
- The main font size and font itself;
- Font sizes and fonts of the titles.

A conclusion, a bibliography list and an exhaustive summary of the thesis in Estonian are mandatory according to the UT regulations. It is also hard to conceive a thesis without an introduction. Sections with title “CURRICULUM VITAE”, “ELULOOKIRJELDUS” (Curriculum Vitae in Estonian) and “LIST OF ORIGINAL PUBLICATIONS” belong to the format of Dissertationes informaticae Universitatis Tartuensis series and should not be omitted. In a dissertation of the collection type, the subsection “Publications included in the thesis” should list all papers whose reprints are included in the thesis and no others. Other original publications may be listed in separate subsections. Every reprinted publication in section “PUBLICATIONS” should be preceded by a separate page containing its full publication record.

### Tolerable changes

- UT Press prefers to get the dissertation PDF files with a4 paper size. This means that the text area is much smaller than the page. The page will be cut to the right size by the Press. During writing, however, you may obtain a more adequate appearance of the result if you replace “a4paper” with “b5paper” in the class file. This change does not harm any other measures.
- The order of parts is intended to normally be as it is shown in the examples. Please modify it with responsibility and care. Note that the order of parts is slightly different in monograph and collection types of the thesis, as are some parts themselves different. This is intentional, too. So please make sure to use the right template by calling the ThesisType command with the right value when you start writing!
- Numbering of chapters is also intended to normally be as specified in the template. So, an abstract, list of contents, list of figures, tables and abbreviations, bibliography, acknowledgement, summary in Estonian, and CV should not be numbered, while the introduction and conclusion should preferably be numbered. The principle behind this choice is that both the introduction and conclusion are parts of the thesis. If you find this principle not being true, you may omit numbers of the introduction and conclusion, too. The recommended style of numbering uses arabic numbers in the main part and Latin alphabet for appendices. You are free to change it if you prefer.
- The only titles that are expected to be substituted are “Dissertation title”, “CONTENT CHAPTER TITLE”, “APPENDIX TITLE” and “Töö pealkiri” (the latter should be substituted by the title of the thesis in Estonian). So please do not normally substitute, for instance, “SISUKOKKUVÕTE” (Summary in Estonian). Substituting, e.g., “INTRODUCTION” and “CONCLUSION” by something more precise is tolerable under good reasons.
- Abstract, list of figures, list of tables, list of abbreviations, preface and acknowledgement may be omitted. In a dissertation of the collection type, not all subsections of “LIST OF ORIGINAL PUBLICATIONS” given in the example are mandatory. If you only list publications whose reprints are included in the thesis, please remove the subsection and rename the section title to “PUBLICATIONS INCLUDED IN THE THESIS”.
- The student may use any reference style out of the three standard ones. Likewise, choice of the format of the bibliographic records in the bibliography section, list of publications, and before each reprinted publication (in a thesis of the collection type) is up to the author of the thesis. The same style must be used throughout the thesis.
- In a thesis of the collection type, it is recommended to include each publication also in the general list of contents of the thesis, as shown in the example. Alternately, a separate list of contents for the reprinted publications may be created.


### Authors
The LaTeX class file and templates have been created by Reimo Palm, following the traditions of the Institute of Computer Science of UT and guidelines of UT Press.
