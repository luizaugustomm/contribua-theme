This is the Contribua theme, based on Pybossa's defalt theme.

# Translations

If you want to enable the translations for your PyBossa server, you'll have to create 
a symbolic link of the translations folder into the pybossa root folder:

```bash
ln -s pybossa/themes/pybossa-default-theme/translations pybossa/translations
```

Then, restart the server and you'll be done. NOTE: be sure to enable/disable the
locales that you want to use.

# Creating a new theme

In order to create a new theme, fork this repository and make all the required
changes in the **templates** and **static** folder.
