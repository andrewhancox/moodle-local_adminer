# Moodle Plugin "local_adminer"
## General
This plugin is based on the great tool adminer. The main advantage of this plugin is, it can handle different types of database. So it works with MySQL, PostgreSQL, Oracle and MSSQL. Here are some of the key-features:

1. you can define trigger
1. you can change the order of fields
1. you can easy create or alter views
1. you can create stored procedures
1. if you rename a database so the database is altered and not copied like phpMyAdmin it does
1. you can define foreign key with referential integrity

## Git structure
Because of different needs there are two structures in this repository.
### Moodle plugin database
The branches **MOODLE_XY_STABLE** are suitable to the moodle plugin databases. All Files are in the root path of the plugin itself.  
`./`  
&nbsp;&nbsp;&nbsp;&nbsp;`lang/`  
&nbsp;&nbsp;&nbsp;&nbsp;`lib/`  
&nbsp;&nbsp;&nbsp;&nbsp;`version.php`  

To use these branches you can put it as a submodule into your moodle repository.
## Subtree
The branches **v_XY_subtree** are suitable for simple merging into an existing moodle repository.  
`./`  
&nbsp;&nbsp;&nbsp;&nbsp;`local/`  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`adminer/`  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`lang/`  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`lib/`  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`version.php`  
