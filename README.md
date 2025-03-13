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
