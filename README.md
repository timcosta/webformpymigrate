webformpyexport
===============

Export a Drupal Webform Node into JSON and import it to another installation. Supports the Webform Validation module.

This is a python script invoked from the command line that will export any existing Webform and its node and validations into a JSON file. This file can then be used to import the webform to another drupal installation.

This script includes support for the Webform Validation module.

Use -e to run the export script.

Use -i to run the import script. Supports --debug which prints all MySQL queries as they are executed.
