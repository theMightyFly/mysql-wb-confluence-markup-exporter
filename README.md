mysql-wb-confluence-markup-exporter
===================================

Generating MySQL Database Documentation for Confluence with MySQL Workbench Plugin

http://ralf.schaeftlein.de/2011/02/24/generating-mysql-database-documentation-for-confluence-with-mysql-workbench-plugin/

Howto:

Download this Script
Start your MySQL Workbench
Choose from the “scripting” menu the entry “Install Plugin/Module…”
Change Drop down in the Dialog to File type ”lua Files..”
Choose downloaded File and click open
Restart Workbench
Open previously generated ER model file *.mwb
Choose from the “Plugins” menu the entry “Catalog” and their the new entry “Confluence Markup Exporter…”
Markup is now in the clipboard
Open in Confluence an existing page or create a new onw
Click on “Edit” button and go to tab “Wiki Markup”
Paste the generated documentation and click on “save” button