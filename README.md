# Comau-syntax-npp
#### Syntax highlighting of Comau robot language PDL2 for Notepad++

Being tired of the old style, black and white, not zoomable text editor application from Comau (WinC4G, WinC5G, WinR1C, ...)
I decided to develop my own syntax highlighting fro Notepad++.
At first I used the common statement and reserved word from the Comau programming manuals.
Step by step I included all the built-in, system variables and other keywords I could find in various robot programs, controller system files, etc...
Now the list comprehend a lot of entries, some of them are for old controller versions (WinC5G) and are not used by the new versions (WinR1C).
Please inform me if you find some keyword that is not correctly highlighed.

### Content of the repository

- "COMAU_Syntax_PDL.xml" is the xml file descriptor for Comau program file .pdl

- "COMAU_Syntax_LSV.xml" is the xml file descriptor for Comau variables file .lsv

- "COMAU_Syntax_Keywords.xlsx" is an excel listing of all highlighted keywords divided by type 


### Use on Notepad++ 
Menu Bar Language/User Defined Language/Define your language... --> Import...
Then choose COMAU_Syntax_PDL.xml and later COMAU_Syntax_LSV.xml




