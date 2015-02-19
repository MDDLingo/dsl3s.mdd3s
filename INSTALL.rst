# 1. Add templates and services packages as exported
 - Open MANIFEST.MF
 - Go to "Runtime" tab
 - Use "Add" button to export the two packages
 
# 2. Set singleton to true
 - Open MANIFEST.MF
 - Go to "MANIFEST.MF" tab
 - Add singleton=true to SymbolicName; the line should look like:
   Bundle-SymbolicName: dsl3s.mdd3s; singleton:=true
   
# 3. Force compilation
 - Open UML2Services and change something
 - Save file (check in bin folder that compilation took place)
 - Might need to do the same in the templates package
 
# 4. At the end there should be no errors or warnings in this project
