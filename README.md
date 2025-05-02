# biochar-review
Bibliometrix data on biochar literature review. Data collected March 22, 2025

Process:
Search Web of Science for all literature with the keywords "Biochar pyrolysis mechanism"

Export data as multiple Bibtex documents

Download RStudio

Combine Bibtex documents together to create one main file. This was done by copying and pasting info into one file. (Raw data also present on main page in compressed folder)

Install bibliometrix with biblioshiny

in RStudio, use the following code:
library(bibliometrix)
biblioshiny()

This opens the biblioshiny web interface

Click on "Data" and then select "Import or Load"

Select "import raw file" from dropdown menu on the right and check that the correct database is chosen

Upload file and hit run to recieve bibliometric results
