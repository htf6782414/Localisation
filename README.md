<!--TO VIEW THE DOCUMENT CORRECTLY: USE LINE WRAP METHOD "NO WRAP"-->
<!--   Lines within these brackets are invisible and guides you   -->

# Localisation
This repository is for the translation of OpenRCT2 into other languages.<br/>
For the main development and codebase of OpenRCT2, visit [OpenRCT2/OpenRCT2](https://github.com/OpenRCT2/OpenRCT2).

OpenRCT2's base language is English (UK), this is updated and maintained in the main repository.<br/>
Other languages are maintained in this repository.<br/>
Changes to the master branch are merged into the develop branch of OpenRCT2/OpenRCT2 every day at 4:00 AM UTC.

### Chat
[![Gitter](https://img.shields.io/badge/gitter-general-blue.svg)](https://gitter.im/OpenRCT2/OpenRCT2/non-dev)<br/>
[![Gitter](https://img.shields.io/badge/gitter-localisation-green.svg)](https://gitter.im/OpenRCT2/Localisation)<br/>
[![Gitter](https://img.shields.io/badge/gitter-development-yellowgreen.svg)](https://gitter.im/OpenRCT2/OpenRCT2)

### Build Status
[![AppVeyor](https://ci.appveyor.com/api/projects/status/fkf22bp6tw8lxg6m?svg=true)](https://ci.appveyor.com/project/OpenRCT2/localisation)

To contribute to the translation of OpenRCT2, you will need to fork this repository.<br/>
This allows you to edit and push changes of files to your fork so that you can then open a pull request.<br/>
For more information, visit GitHub's official [forking guide](https://guides.github.com/activities/forking/).

### Creating a new language
If you want to begin translating OpenRCT2 for a new language, create a new file in the data directory with the correct two letter [language](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes#Partial_ISO_639_table) and [country codes](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2#Decoding_table) (e.g. `cs-CZ`), then paste the contents of the [en-GB](https://github.com/OpenRCT2/OpenRCT2/blob/develop/data/language/en-GB.txt) file into it and start translating the strings.

### Maintainers & Maintaining languages
As this project always are moving forward, new strings get added from time to time which means they need to be added to the language files and be translated. All the new strings that are being added can be found in ['issues'](https://github.com/OpenRCT2/Localisation/issues) on the localisation webpage here on GitHub. To be a maintainer means that you have to add the new strings found on the issues page into the language you're translating in numerical order.

If you want to become a maintainer, tell us what language you will maintain on [Gitter](https://gitter.im/OpenRCT2/Localisation)

### Checking & testing strings in-game
You can always test the translated strings in-game before publishing a pull request which could be good if the string has limited space/has a ``<newline>`` formating in it.<br/>
One simple way to test the new language is to copy the whole document you've translated and go to your games ``\OpenRCT2\data\language`` folder and paste the copied text into the language you want to test.

### Language Status
| Newest strings can be found in [issues](https://github.com/OpenRCT2/Localisation/issues) | 
| -----------------------------------------------------------------------------------------| 

| Language | Maintainer | Status Bars |
| -------- | ---------- | ----------- | 
| [![](https://img.shields.io/badge/ar--EG-maintained-green.svg)](https://github.com/OpenRCT2/Localisation/blob/master/data/language/ar-EG.txt) | [Omaranwa](https://github.com/Omaranwa)          | ![](https://api.openrct2.website/localisation/status/badges/ar-EG) | 
| [![](https://img.shields.io/badge/da--DK-maintained-green.svg)](https://github.com/OpenRCT2/Localisation/blob/master/data/language/da-DK.txt) | [LPSGizmo](https://github.com/LPSGizmo)          | ![](https://api.openrct2.website/localisation/status/badges/da-DK) | 
| [![](https://img.shields.io/badge/en--GB-maintained-green.svg)](https://github.com/OpenRCT2/OpenRCT2/blob/develop/data/language/en-GB.txt   ) | -Anyone-                                           | ![](https://api.openrct2.website/localisation/status/badges/en-GB) | 
| [![](https://img.shields.io/badge/ca--ES-maintained-green.svg)](https://github.com/OpenRCT2/Localisation/blob/master/data/language/ca-ES.txt) | [J0anJosep](https://github.com/J0anJosep)          | ![](https://api.openrct2.website/localisation/status/badges/ca-ES) | 
| [![](https://img.shields.io/badge/cs--CZ-maintained-green.svg)](https://github.com/OpenRCT2/Localisation/blob/master/data/language/cs-CZ.txt) | [octaroot](https://github.com/octaroot)            | ![](https://api.openrct2.website/localisation/status/badges/cs-CZ) | 
| [![](https://img.shields.io/badge/de--DE-maintained-green.svg)](https://github.com/OpenRCT2/Localisation/blob/master/data/language/de-DE.txt) | [danidoedel](https://github.com/danidoedel)        | ![](https://api.openrct2.website/localisation/status/badges/de-DE) | 
| [![](https://img.shields.io/badge/es--ES-maintained-green.svg)](https://github.com/OpenRCT2/Localisation/blob/master/data/language/es-ES.txt) | [Wirlie](https://github.com/Wirlie), [frenchiveruti](https://github.com/frenchiveruti)                | ![](https://api.openrct2.website/localisation/status/badges/es-ES) | 
| [![](https://img.shields.io/badge/fr--FR-maintained-green.svg)](https://github.com/OpenRCT2/Localisation/blob/master/data/language/fr-FR.txt) | [JoelTroch](https://github.com/JoelTroch)          | ![](https://api.openrct2.website/localisation/status/badges/fr-FR) | 
| [![](https://img.shields.io/badge/hu--HU-maintained-green.svg)](https://github.com/OpenRCT2/Localisation/blob/master/data/language/hu-HU.txt) | [anon569](https://github.com/anon569)              | ![](https://api.openrct2.website/localisation/status/badges/hu-HU) | 
| [![](https://img.shields.io/badge/it--IT-maintained-green.svg)](https://github.com/OpenRCT2/Localisation/blob/master/data/language/it-IT.txt) | [LucaRed](https://github.com/LucaRed)              | ![](https://api.openrct2.website/localisation/status/badges/it-IT) | 
| [![](https://img.shields.io/badge/ja--JP-maintained-green.svg)](https://github.com/OpenRCT2/Localisation/blob/master/data/language/ja-JP.txt) | [AaronVanGeffen](https://github.com/AaronVanGeffen)| ![](https://api.openrct2.website/localisation/status/badges/ja-JP) | 
| [![](https://img.shields.io/badge/ko--KR-maintained-green.svg)](https://github.com/OpenRCT2/Localisation/blob/master/data/language/ko-KR.txt) | [telk5093](https://github.com/telk5093)            | ![](https://api.openrct2.website/localisation/status/badges/ko-KR) | 
| [![](https://img.shields.io/badge/nb--NO-maintained-green.svg)](https://github.com/OpenRCT2/Localisation/blob/master/data/language/nb-NO.txt) | [Goddesen](https://github.com/Goddesen)            | ![](https://api.openrct2.website/localisation/status/badges/nb-NO) | 
| [![](https://img.shields.io/badge/nl--NL-maintained-green.svg)](https://github.com/OpenRCT2/Localisation/blob/master/data/language/nl-NL.txt) | [Gymnasiast ](https://github.com/Gymnasiast )      | ![](https://api.openrct2.website/localisation/status/badges/nl-NL) | 
| [![](https://img.shields.io/badge/pt--BR-maintained-green.svg)](https://github.com/OpenRCT2/Localisation/blob/master/data/language/pt-BR.txt) | [renansimoes](https://github.com/renansimoes)      | ![](https://api.openrct2.website/localisation/status/badges/pt-BR) | 
| [![](https://img.shields.io/badge/sv--SE-maintained-green.svg)](https://github.com/OpenRCT2/Localisation/blob/master/data/language/sv-SE.txt) | [Nubbie](https://github.com/Nubbie)                | ![](https://api.openrct2.website/localisation/status/badges/sv-SE) | 
| [![](https://img.shields.io/badge/tr--TR-maintained-green.svg)](https://github.com/OpenRCT2/Localisation/blob/master/data/language/tr-TR.txt) | [BobbyS38](https://github.com/BobbyS38)                | ![](https://api.openrct2.website/localisation/status/badges/tr-TR) | 
| [![](https://img.shields.io/badge/zh--CN-maintained-green.svg)](https://github.com/OpenRCT2/Localisation/blob/master/data/language/zh-CN.txt) | [izhangfei](https://github.com/izhangfei)          | ![](https://api.openrct2.website/localisation/status/badges/zh-CN) | 
| [![](https://img.shields.io/badge/zh--TW-maintained-green.svg)](https://github.com/OpenRCT2/Localisation/blob/master/data/language/zh-TW.txt) | [daihakkeni](https://github.com/daihakken)         | ![](https://api.openrct2.website/localisation/status/badges/zh-TW) | 
| Not maintained <!-- Languages that are outdated with strings missing from OpenRCT2/vanilla-->| |                                                 
| [![](https://img.shields.io/badge/fi--FI-outdated-yellow.svg)](https://github.com/OpenRCT2/Localisation/blob/master/data/language/fi-FI.txt)  |                                                    | ![](https://api.openrct2.website/localisation/status/badges/fi-FI) | 
| [![](https://img.shields.io/badge/pl--PL-outdated-yellow.svg)](https://github.com/OpenRCT2/Localisation/blob/master/data/language/pl-PL.txt)  |                                                    | ![](https://api.openrct2.website/localisation/status/badges/pl-PL) | 
| [![](https://img.shields.io/badge/ru--RU-outdated-red.svg)](https://github.com/OpenRCT2/Localisation/blob/master/data/language/ru-RU.txt)     |                                                    | ![](https://api.openrct2.website/localisation/status/badges/ru-RU) | 

| en-US only contains strings that differ from en-GB <!--en-US doesn't get updated more than it's needed-->           
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | 
| [![](https://img.shields.io/badge/en--US-maintained-green.svg)](https://github.com/OpenRCT2/Localisation/blob/master/data/language/en-US.txt) |         -Anyone-         | ![](https://api.openrct2.website/localisation/status/badges/en-US)  |

Note:  The status bars can be inaccurate & some maintainers can be more inactive than others.<br/>
Anyone can still contribute to the languages. 

### Questions & Support

If you have any question or issues, please don't hesitate at contacting us at<br/>
[![Gitter](https://img.shields.io/badge/gitter-localisation-green.svg)](https://gitter.im/OpenRCT2/Localisation)<br />
