# folderstructuur
## data
* abiotiek: omgevingsdata
* biotiek: biotische data
  * vis: alle visdata
    * edna: environmental DNA data
      * extern: externe data (gecreerd buiten R project)
      * intern: interne data (gecreerd binnen R project) 
    * elektrisch: alle data van het elektrisch vissen
      * extern: externe data (gecreerd buiten R project) met onderscheid tussen ruw (oorspronkelijke data) verwerkt_in_excel (correctie voor eventuele fouten in de data)
      * intern: interne data (gecreerd binnen R project) 
## output
opslag build bookdown
## source
* functions
  * f.read_excel_allsheets.R: leest in alle aparte worksheets van een excel en plakt deze aanmekaar in 1 dataframe
* not_functions
  * add_missing_folders.R: creert eventuele folders die ontbreken in de directory (handig wanneer het project voor de eerste keer gekloond wordt van github)
## gitignore
Aangeven welke files niet gecommit en gepushed mogen worden
## bookdown.yml
file nodig voor build met specs
## 000_abstract.Rmd
## 001_resume.Rmd
## 01_inleiding.Rmd
## 021_methodologie_abiotiek.Rmd
## 022_methodologie_vissen_elektrisch.Rmd
## 023_methodologie_vissen_edna.Rmd
## 031_resultaten_abiotiek.Rmd
## 032_resultaten_vissen_elektrisch.Rmd
## 033_resultaten_vissen_edna.Rmd
## cover.txt
## ehs_kesterbeek_2024.Rproj
## index.Rmd
## LICENSE.md
## references.bib
## zzz_references_and_appendix.Rmd
