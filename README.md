# i18n
Internationalisation for vwa.la. Contributions welcome!

How to contribute
=================

Non-technical users
-------------------

**Editing a language translation file**

1. Create a github.com account 
1. Click on any *.json langauge file in the above table to view it's contents. Each file contains translations from English into another language (i.e. de = German, see the section below for a table of contents). 
2. Click the edit button to start editing (right side menu) ![Click the edit button to start editing](docs/screen-edit-file.png?raw=true "Click the edit button to start editing")
3. Make your changes to the file. Please do not change the English parts on the left of the colon : character. Only change the parts on the right side and make sure to preserve the "" characters at the start and end of the translation text.
4. To save your changes, scroll to the bottom of the page and select **Create new branch for this commit...** and then click **propose file change** to submit your edits. Make sure you leave a comment describing your changes ![Click save changes to submit your edits](docs/screen-save-changes.png?raw=true "Click save changes to submit your edits")
4. Done. We will then review your edits and release an update :)

Technical users
---------------

**1. Download and edit language files**

1. https://git-scm.com/downloads
2. Open a command line window 
3. `git clone https://github.com/vwala/il8n.git`
4. Edit the langauge files (*.json extension)

**2. Publish your changes**

*Remember to add a valid comment*

`
git add * && git commit -m "type your comment here" && git push
`


# File summary

*language*.*app_page*.json


| File name                | Web page                    | 
|--------------------------|-----------------------------| 
| de.createA.json          | Influencer signup page      | 
| de.db.a.home.json        | Influencer homepage         | 
| de.db.a.json             | Influencer table            | 
| de.db.table.a.json       | Influencer table            | 
| de.db.ac.json            | Influencer code table       | 
| de.db.table.ac.json      | Influencer code table       | 
| de.db.account.json       | My account page             | 
| de.db.account.store.json | My account > store settings | 
| de.db.account.user.json  | My account > user settings  | 
| de.db.menu.json          | App menu                    | 
| de.db.nodata.json        | No table data page          | 
| de.db.o.json             | Order table                 | 
| de.db.table.o.json       | Order table                 | 
| de.db.ob.json            | Onboarding guide            | 
| de.db.p.json             | Promotion policy page       | 
| de.db.s.home.json        | Merchant homepage           | 
| de.db.sma.json           | Socia media accounts table  | 
| de.db.table.sma.json     | Socia media accounts table  | 
| de.db.table.v.json       | Leads table                 | 
| de.db.v.json             | Leads table                 | 
| de.login.json            | Login page                  | 

**Languages**

| ISO code |  Langugage   | 
|----------|--------------| 
| de       | German       | 
| pt       | Portugese    | 
| pt-br    | Brazillian   | 
| zh       | Chinese      | 
| en       | English      | 
| fr       | French       | 
| es       | Spanish      | 


Misc
----

find . -name '*_old.json' -delete