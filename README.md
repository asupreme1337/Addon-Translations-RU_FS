# Addon-Translations
This is the repo where some of my more recent addons get they're translations from. This allows translations to be edited/updated without updates to the addon, making updates faster and less frequent for users with just patches for translations.

## Contibuting
Project structure is like this:  
```
📂Addon 1  
    📝versions.json  
    📂1.0.0  
        📝English.json  
        📝French.json  
    📂1.0.1  
        📝English.json  
        📝French.json  
    📂1.1.0  
        📝English.json  
        📝French.json  
📂Addon 2
    📝versions.json
    📂1.0.0
        📝English.json
        📝German.json
    📂1.0.1
        📝English.json
        📝German.json
    📂1.1.0
        📝English.json
        📝German.json
```
Each folder contains a different addon. Each addon contains a version.json file, which directs the addon where to find translations for it's current verison (You won't need to worry about this, I'll update it myself). Inside that same folder, is folders relating to each addon version. Inside each version is a json file with the translations you need to edit.  
If you make a translation, submit it in a PR (or just commit it if your already a contributor) and it'll be available in the addon almost instantly. Cool, huh?
