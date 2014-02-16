# XyllabusML: A Syllabus Markup Language #

This repository contains working code for a universal course syllabus markup language, tentatively called Xyllabus.

## Motivation ##

Course syllabi are an integral part of contemporary higher education. They communicate almost all of the information about the content, objectives, outcomes, and prerequisites of a course. Syllabi should be open and shared - writing a syllabus from scratch is largely reinventing the wheel for the vast majority of courses. Yet, syllabi are almost always shared in proprietary or at least closed-source formats (e.g., Word or sourceless LaTeX-generated PDFs). The aim of this project is to develop an XML schema for the course syllabus, which is sufficiently general to contain all of the content that might find its way into a syllabus for any discipline, institution, and course format.

## Current Stage ##

Drafting the schema and trying out the markup.

## Next steps ##

 1. XSLT (XSL Transform) templates for writing to LaTeX, ODF, Markup, HTML, etc.
 2. BibTeX and DOI integration for assigned texts
 3. Some kind of interface to write valid Xyllabus XML files
 4. Write scrapers to transform existing syllabi into Xyllabus.
 5. Setup a syllabus archive

## Contribute! ##

This project is in its very initial stages, so all comments, suggestions, and pull requests are welcome.

## License ##

This project is released under the [Creative Commons Attribution 3.0 license](http://creativecommons.org/licenses/by/3.0/).
