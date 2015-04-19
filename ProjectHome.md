This repository holds the English and all translated strings for the GSam Battery Monitor android app.

Interested in translating GSam Battery Monitor?  Contact the the author (gsamtan +At= +gmail dot +com).

Already a translator?  You should have Commit authority - you can either user SVN or the googlecode web interface to upload the appropriate Strings file.  Let me know when you have an update, and I'll crank a build for you to verify the translation.

# Translator Instructions #
  1. Access the repository.   You should have full access once you've provided a gmail ID. http://code.google.com/p/gsam-battery-monitor-translation
  1. View or download the English version of the strings.xml file [here](http://code.google.com/p/gsam-battery-monitor-translation/source/browse/%20gsam-battery-monitor-translation/BadassBatteryMonitorTranslation/res/values/strings.xml).  You can get the 'raw' file to download by clicking on the Raw File link.
  1. Add (or modify) your language specific strings.xml by going to the above [URL](http://code.google.com/p/gsam-battery-monitor-translation) -> Source -> Browse -> svn / gsam-battery-monitor-translation / BadassBatteryMonitorTranslation / res.  In here you'll see the values-XX (if not, create one).  You can edit the files directly, or upload a file.  **EG:** Russian is located [here](http://code.google.com/p/gsam-battery-monitor-translation/source/browse/%20gsam-battery-monitor-translation/BadassBatteryMonitorTranslation/res/values-ru/strings.xml)
  1. You can modify a file directly.  Don't add a new file for every new version, instead just edit the existing one.  Just copy/paste the entire file in again.
  1. If you're comfortable editing / adding an xml file into an existing APK and resigning it you can do that to validate, otherwise just let me know and I'll crank out a build with the latest file you uploaded.  A good tutorial on how to edit an existing APK is available [here](http://www.miui-au.com/add-ons/apktool/), however it's not for the faint of heart.
  1. There is a language option in the preferences of GSam Battery Monitor now that let's you override your default phone locale for the app if you want - it's useful for validating the various languages.
  1. The about screen will include a list of all translated languages as well as an optional translators name & HTML link.  If you want to remain anonymous, just don't add the 'translator\_XX' string key.
  1. I'll publish a new strings.xml file every new build of the battery monitor.  I'll pull in whatever the latest version of the translated files are at that point in time.
  1. You can view differences between versions of the English strings file to see what has changed since last translated by going to the english strings file [here](http://code.google.com/p/gsam-battery-monitor-translation/source/browse/%20gsam-battery-monitor-translation/BadassBatteryMonitorTranslation/res/values/strings.xml).  Look in the **Change Log** box on the right hand side, and for each version you'll see a _diff_ link that will show you details of what changed so you can update the translated version accordingly.
  1. **NOTES:**
  * If you're familiar with Subversion, feel free to use it directly rather than going through the web interface.
  * If it's simpler for you, you can always simply grab the latest English file [here](http://gsam-battery-monitor-translation.googlecode.com/svn/%20gsam-battery-monitor-translation/BadassBatteryMonitorTranslation/res/values/strings.xml), translate it as you normally would, and email me a copy of the translated strings.


---

