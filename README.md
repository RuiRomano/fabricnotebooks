# fabricnotebooks

## This repo provides a collection of jupyter notebooks showing examples of manipulating reports using a pbip format.

# Demo 1 - Translate Report - Creates list of reports translated using Azure AI Translator
Notebook uses semantic link to acquired the definition of all the report parts. A list of visual titles are collected. From the collection of visual titles AI translator is used to translate each title into different languages, fr, it, pt, and ja.

Reports are then copied and each title of visuals are translated into each language. 

# Demo 2 - SwapLogo - Read Definition of reports and swap a logo on each report
Using the getDefinition API for a report list all parts. Load an icon from github. Then using the base64 definition of the icon find a specific report part that is an image, then replace each image with the newly loaded image.
