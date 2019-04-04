# Cordova Plugin for iOS Localisations
This plugin is used to localise your iOS app's contents & other assets like app permission texts

# Usage
1) Fork this plugin
2) In order to localise your app's permissions, edit the "InfoPlist.strings" file on the respective language folder (e.g. For German Language, edit the "InfoPlist.strings" file inside "src/ios/de.lproj/.." path.
3) If you want to add a new language, you should create a folder named with your language name (e.g. for German language, you should create the "de.lproj" folder) and a file named "InfoPlist.strings" which will contain your localised permission keys.
The folder with the file should be placed under the following directory: "src/ios/<your_language_name>.lproj/.."
Then you should add the file reference in plugin.xml on the respective folder filepath of your created translations (e.g. 'resource-file src="src/ios/DMCMediaPicker/de.lproj"'). 
For more info see plugin.xml.
