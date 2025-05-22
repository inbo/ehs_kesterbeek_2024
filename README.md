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
## media
pictures
## output
rapport in pdf
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
Engelstalige samenvatting
## 001_resume.Rmd
Franstalige samenvatting
## 01_inleiding.Rmd
## 021_methodologie_abiotiek.Rmd
Methdologie beschrijving voor verzameling hydromorfologie-data
## 022_methodologie_vissen_elektrisch.Rmd
Methdologie beschrijving voor het elektrisch vissen
## 023_methodologie_vissen_edna.Rmd
Methdologie beschrijving voor het verzamelen en verwerken van eDNA-stalen
## 031_resultaten_abiotiek.Rmd
Verwerking hydromorfologie data
## 032_resultaten_vissen_elektrisch.Rmd
Verwerking data elektrisch vissen
## 033_resultaten_vissen_edna.Rmd
Verwerking data eDNA
## cover.txt
Informatie voor beginpagina rapport 
## ehs_kesterbeek_2024.Rproj
R Project (open het r project altijd via deze weg)
## index.Rmd
Overkoepelende file met alle nodige info om het rapport te creëren
## LICENSE.md
Type licensie voor hergebruik data en code
## references.bib
Overzicht van de referenties van het rapport
## zzz_references_and_appendix.Rmd
Link naar referentie met bibliografie en appendix
