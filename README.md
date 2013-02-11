mysql-wb-confluence-markup-exporter
===================================

Generating MySQL Database Documentation for Confluence with MySQL Workbench Plugin

http://ralf.schaeftlein.de/2011/02/24/generating-mysql-database-documentation-for-confluence-with-mysql-workbench-plugin/

Howto:

1. Download an Exporter Script
2. Start your MySQL Workbench
3. Choose from the “scripting” menu the entry “Install Plugin/Module…”
4. Change Drop down in the Dialog to File type ”lua Files..”
5. Choose downloaded File and click open
6. Restart Workbench
7. Open previously generated ER model file *.mwb
8. Choose from the “Plugins” menu the entry “Catalog” and their the new entry “Confluence Markup Exporter…”
9. Markup is now in the clipboard
10. Open in Confluence an existing page or create a new onw
11. Click on “Edit” button and go to tab “Wiki Markup”
12. Paste the generated documentation and click on “save” button

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.