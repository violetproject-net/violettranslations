# Violetproject Locations And Translations

This is the repository for simplifying the translation and location mapping process for the site and locations in games hosted on the site, as well as making the already made translations more accessible, 

# [Credits](CREDITS.md)

Site UI translations are in /gamepage/lang

Game locations + location translations are in /locations

Check to make sure a language is not already translated fully before making a translation :3 

# UI Translations

To make a UI translation, download sitetemplate.json and fill out the first three lines.

The first line should have the two letter code for the language. 
The second line should have the language name, in the language that it is for, example being Español (correct) instead of Spanish (incorrect)
The third line is for right to left formatting. This should usually stay false besides specific languages.

Then, replace all the strings below with the translation for your language which you are translating (Make sure to only edit the text on the right, which shows up blue in VS Code)

Once you have translated all the text, rename the file to your two letter language code from before (example: en.json)
Then. make a pull request to this repository (file should be in /gamepage/lang/ or send it to me on discord at "violetsitas".

# Location Translations

To make a location translation for a game, download the games base location file first. 

Then, replace all the map names with the target languages translation.

After that, rename the file to gamename_twolettercode (example: blackrain_ja) and make a pull request here (file should be in /locations) or send it to me on discord at "violetsitas"

# Locations

If you want to help with the location mapping itself, you can edit the base file for a game and add location names there linked to the map id, or edit the location names if they are incorrect or outdated

Then, make a pull request replacing the file, or send it to me on discord at "violetsitas"
