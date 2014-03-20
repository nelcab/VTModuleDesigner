VTModuleDesigner
================

> ****************************************************************
> WARNING : VTModuleDesigner does not work with magic_quotes_gpc()
> ****************************************************************

# How to
Video tutorial : [http://youtu.be/PF3noyh7M-g](http://youtu.be/PF3noyh7M-g)

# Customize your Module Designer
Module Designer for Vtiger 6

You can set your own fields and variables. To do this modify these files:
- /vlayouts/layout/Settings/ModuleDesigner/Custom.tpl
- /vlayouts/layout/Settings/ModuleDesigner/resources/CustomScript.js
- /modules/ModuleDesigner/CustomManifestStructure.php

You can also create plugins to handle your variables, in the directory /modules/ModuleDesigner/plugins

******************************************************************
******************************************************************
NOTE:

This fork it's the same version of VTModuleDesigner, but I just made a simple change to 
the default French language option (when you create new modules), so it will support 
Spanish (MX) language instead. This will provide a faster way to deploy directly from 
VTModuleDesigner on their own language for Spanish/MX users.

All development credit goes to its original creators.