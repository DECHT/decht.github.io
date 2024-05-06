# landing-page

## How to generate HTML multilanguage files with ` static-i18n `
#### Install static-i18n
```
sudo npm install -g static-i18n
```
#### Generate HTML files
The main HTML file with translatable variables is in the folder ` www `, there you can also find a folder with translations in YAML format. 
```
static-i18n --fileFormat yaml -i en -i de www
```
This command will create a new folder ` i18n ` with HTML files. The roots are not compatible with the static files, so you have to move the generated english HTML file and the folder(s) with other HTML files into the root folder to open the HTML site on your computer.
