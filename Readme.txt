
YOU NEED A CONSTANT INTERNET CONNECTION TO SUCCESSFULLY EXECUTE MOST OF THE STEPS LISTED BELOW

install nodeJs: go to www.nodejs.org and download the one for the os you are using and then add it to the path. Here is the procedure to add it to the path:

- go to "panneau de configuration"/"control panel"
- go to advanced system settings. To ease the task, type "variables" in the search field (I think it's found under "advanced system settings")
- click on "variables d'environement" / "environment settings"
- two fields appear, in the one labelled "variables systeme"/ "system variables" click "nouvelle"/ "new"
- copy the path where the nodejs was installed and paste it to the field labelled "valeur de variable"/ "variable value" and in the field labelled "nom de la variable"/"variable name" write any name you choose then save

next
open the command line and type

- cd  <folder_name>
	For this command, i advice you save the folder on your desktop. if that's the case, perform the following; 
	* cd Desktop press ENTER
	* cd SSI press ENTER

-  npm install ENTER

- bower install ENTER

- npm install -g grunt grunt-cli ENTER

- grunt serve ENTER
normally the application should automatically be launched in the browser.