# Spagobi translation to Polish

Translation SpagoBI 5.2.0 to Polish language

In order to localize SpagoBI in Polish language, you have to follow the below instructions.

## Configure the new language
Log into SpagoBI as Administrator

Go to Tools - Manage Configurations

In the Select Category combo box, select "LANGUAGE_SUPPORTED"

Add the language at the end of the existing string as follows: ,[pl,PL]

Add the icon of the related flag into the file: 
```sh
    SpagoBI\themes\sbi_default\css\analiticalmodel\execution\main.css
```
by adding the following lines:
```sh
    .icon-pl {
      background-image: url('../../../img/flags/pl_PL.gif') !important;
    }
```
## Copy files
Files from repo need to be copied to webapps dir
