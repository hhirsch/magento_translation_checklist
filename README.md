# Magento Translation Checklist
- The order of translation loading is from database, from theme and then from module. Check if the translations you want are getting overwritten.
- Compare your config.xml with a config of a module that you know has working translations.
- Compare your file locations and path names with a module where translations are working.
- Are the file names and paths the same as in the config?
- If you are using composer or something similar, are all the files copied or linked correctly?
