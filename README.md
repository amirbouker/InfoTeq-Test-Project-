# InfoTeq-Test-Project-
this project is infoteq test project 
Info Teq Planning 


Roles: 
-Amir Bouker: Backend + devOps 
-Domen: FrontEnd + backend
-Ziga: Frontend + backend 

CONTEXT :
This is a platform to monitor a city citizens COVID vaccine engagement 
In other words, we are tracking if a user took the two vaccine shots and the booster with their proper date also the separation is happening based on the grandfather the father, and the son hierarchy way 

TASKS  :
Menu 1 (header menu for the table ) can be reached by clicking on a header element
EditCol :
 we need to define default  values for each column
 when editing data related to that column the changes should be broadcasted throw the entire system and 
Update all the rows’ column with the modification 
NewCol:
Action to create new Col
Save the col 
Cancel the col
DelCol: 
Action to delete a col (with confirmation)
Reorder 
Resize 
ChooseCol: 
Show col 
Hide col 
Drag and drop
FreezeCol:
Freezing all left-hand side !! 
Design part 
Filtercol 
Enable and disable filter mode (parent hierarchy)
Multisort
Enable and disable all kind of sorting
Menu 2 (row menu)
Add Next
Add Child
Del Row
EditRow
multiSelect
Drag and drop
Copy row pink color
Cut row
copy/cut mutliselected 
Past Next
Past child
Generate new id for copied 
BACKEND: I will be needing at least 3 channels  (user, header, and data) 
Questions: when showing/hiding a col should we update all the users? 
Infinite scroll horizontally or vertically? Task 1.e.ii
Notes : 
update only the seen elements first then update the unseen ones 
In header JSON we put the header names and style 



DEV OPS 
Use single repo 
Two folders front end and backend 
Use docker-compose to run the two projects 


