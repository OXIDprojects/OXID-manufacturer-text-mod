# Manufacturer long description for OXID eShops CE
Add a fulltext long description for manufacturers to your oxid eShop.  

Unfortunatly OXID eShops just have a (very) short description field for manufacturers, 
this is where this module comes in and adds a long text description field.  
You even can add a RichText Editor to it.  

## Installation
- Run the migration.sql on your database (Backup all data before you do, just in case)
- Rebuild views: Service -> Tools -> SQL -> "Views jetzt updaten"
- activate module: "Erweiterungen -> Module -> Ivo Bathke: Manufacturer Description"
- in the settings of the module you can switch the display of the description on/off

If you use https://github.com/vanilla-thunder/bla-tinymce Editor, add  
"manufacturer_description" in the "bestlife TinyMCE" configuration for backend classes.

## Usage
After you have activated the module, you will find a tab "Description" in your manufacturers under  :
"Stammdaten -> Hersteller".  
Enter your description there.


## Requirements

- UTF-8
- PHP >= 5.6
- Oxid eShop >= CE 4.9.9

## License MIT

© [Ivo Bathke](https://oxid.ivo-bathke.name)