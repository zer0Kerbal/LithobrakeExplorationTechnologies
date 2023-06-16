---
permalink: /readme.html
title: Localization and Translation Readme
---
<!--
readme.md v2.1.2.1
Localization project
created: 01 Jan 2018
updated: 13 May 2022
updated: 04 Jun 2023

THIS FILE:
    CC BY-ND-4.0
    by [zer0Kerbal](https://gitbug.com/zer0Kerbal)
    inspired by: HebruSan (thank you)
-->

# Translating to your language

![Languages supported by KSP 1.3: English, Spanish, Chinese, Russian, Japanese](https://i.imgur.com/DbCCJWK.png)

The 1.3 release of KSP introduces localization, which allows in-game text to be translated to other languages. This allows more people to enjoy the game in their preferred language and enlarges the community. However, it does not happen automatically for mods; by default, a mod will appear in English regardless of the language of the base game. In order to have both the base game and mods available in the same non-English languages, some additional work must be done by the modder.

Unfortunately, I only speak English, and I maintain this mod for free. This means I cannot create my own translations, and I cannot pay a professional translation service to produce high quality translations. The best I can do on my own is to use Google Translate, which is of dubious value for the terse, idiomatic strings needed in a KSP mod's UI. Instead, I must rely on the expertise of you, the multilingual KSP mod user, to tell me what good translations look like for your language. If you would like to help in this effort, please keep reading to learn how the mod's language files are structured and how to submit translations for use by others.

Note: Even though you will appear to be editing the project's files, don't worry about making mistakes. GitHub will keep your changes separate from the main files until I have verified that they are OK to use. It is even possible for me to ask questions or request changes before your work is committed to the main files.

## Languages

* Supported by Kerbal Space Program as of 1.12.x
  * ![English][EN] English <en-us.cfg>
  * ![Brasil][BR] Brazilian <pt-br.cfg>
  * ![中文][CN] Simplified Chinese (中文) <zh-cn.cfg>
  * ![Deutsch][DE] German (Deutsch) <de.cfg>
  * ![Español][ES] Spanish (Español) <es-es.cfg>
  * ![Français][FR] French (Français)<fr-fr.cfg>
  * ![Italiano][IT] Italian (Italiano) <it-it.cfg>
  * ![日本語][JA] Japanese (日本語) <ja.cfg>
* Included as well
  * ![한국어][KO] Korean (한국어) <ko.cfg>
  * ![Español Mexicano][MX] Mexican Spanish (Español Mexicano) <es-mx.cfg>
  * ![Dutch][NL] Dutch <nl-nl.cfg>
  * ![Norsk][NO] Norwegian (Norsk) <no-no.cfg>
  * ![Polski][PO] Polish (Polski) <pl.cfg>
  * ![Русский][RU] Russian (Русский) <ru.cfg>
  * ![Svenska][SW] Swedish (Svenska) <sw-sw.cfg>
  * ![国语][TW] Taiwanese (国语) <zh-tw.cfg>

## Creating or editing a translation

It is recommended to make your changes on your own computer at first so you can test them before uploading, especially if you are creating a new translation from scratch.

1. Install the current release of xxx mod if you have not already
2. Open your `<KSP_ROOT>/GameData/xxxMod/Localization` folder on your local disk
3. Look for a file called *lang*.cfg, where *lang* is KSP's name for your locale; as of KSP 1.3, this includes:

* en-us (English)
* es-es (Spanish)
* ja (Japanese)
* ru (Russian)
* zh-cn (Chinese)

The remaining steps are different depending on whether the file already exists:

### If the file exists

Follow these steps to make improvements to an existing translation:

4 Edit the file for your language in your favorite text editor
5 Make the changes you wish to see in-game (see the [File format section](#file-format) below for details)
6 Save your changes
7 Remember to [test your changes](#testing)!

### If the file does not exist

Follow these steps to start your own translation from scratch:

4. Make a copy of `en-us.cfg` in the `Localization` folder
5. Rename the file according to the list of languages above
6. Edit the file for your language in your favorite text editor
7. Change the third line from `en-us` to the string for your language (see the [Languages section](#Languages) for details)
8. Translate each string from English to your language (see the [File format section](#file-format) below for details)
9.  Save your changes
10. Remember to [test your changes](#testing)!

### File format

The middle part of the `cfg` file contains the strings to translate. The format is `name = translation`, where the name is a special string defined by the mod. For example:

    #launchSubtitle = Transfers from <<1>>\n(Launch ~<<2>>)

Do **not** change the part to the left of the equals sign ("=")! These names must be the same in every language file.

The part to the right of the equals sign is the string to be used in-game. Most of the text will be shown as-is, but it can contain a few special strings as shown in the [Lingoona grammar module demo](http://lingoona.com/cgi-bin/grammar#l=en&oh=1):

| String  | Purpose                                                                                                                    |
| ------- | -------------------------------------------------------------------------------------------------------------------------- |
| \n      | Line break; try to preserve these based on the original strings to make sure the strings will fit                          |
| <<1>>   | The first substitutable token in the string, will be replaced by a number, name of a planet, etc., depending on the string |
| <<2>>   | Second token, and so on                                                                                                    |
| <<A:1>> | The first token, but substituted with a proper article                                                                     |

For example, this is a possible translation of the above line into Spanish, courtesy of Google Translate:

    #launchSubtitle = Transferencias desde <<1>>\n(Lanzamiento ~<<2>>)

### Testing

It's important to make sure that your changes work correctly. If you use Steam:

1. [Select the language to use in Steam](https://www.youtube.com/watch?v=iBwYCvQxfeI)
2. Wait for the language pack download to complete
3. Run KSP
4. Use the xxxMod ingame and make sure your changes appear as you intended

If you do not use Steam, I don't know the steps to choose a language. Contact SQUAD if you can't figure it out.

## Contributing your translation for others to use

After you have prepared a `cfg` file for your language and confirmed that it works as you intend, if you are willing to contribute it for redistribution under the xxxModd's license, follow these steps to upload it for inclusion in the main mod distribution:

1. Log in to [GitHub](https://github.com); you may need to register an account if you do not already have one
2. Navigate to the xxxMod's Localization folder
3. Look for the file you edited

The remaining steps are different depending on whether the file already exists:

### If the file exists

4. Click the file's name to view it
5. Click the [pencil icon](https://help.github.com/assets/images/help/repository/edit-file-edit-button.png) to edit
6. Replace the text with the pasted contents of the file you edited locally
7. **Important**: At the bottom of the page, under Propose file change, type an English description of the changes you have made and the reason you think they should be made. This will help me to confirm that your changes are appropriate. Remember, I do not speak the language in the `cfg` file, so I need you to tell me why your way is better!
6. Click `Propose file change` at the bottom when done

### If the file does not exist

4. Click [Create new file](https://help.github.com/assets/images/help/repository/create_new_file.png) to create it
5. Enter the correct file name in the box at the top
6. Paste the contents of the file you edited locally into the big box in the middle
8. Click `Propose new file` at the bottom when done

### Review

Once you finish your changes, GitHub will send me a notification that a pull request has been submitted. I will take a look at it within a day or two and attempt to verify that the changes make sense by:

* Confirming that the file name and the third line of the file match one of the supported locale names
* Viewing each changed string in-game
* Checking Google Translate
* Asking individual human experts
* Requesting help on the KSP forum

If I have any questions about specific changes you've made, I will add them to the pull request, which should trigger a notification to you. Please try to respond to these in as timely a manner as you can manage. Your pull request may be closed without merging if you do not reply for a long time.

Once all the questions and comments are resolved to my satisfaction, your changes will be merged into the main files and included in the next release. I will also add your GitHub name to the Acknowledgements section of the README file.

[EN]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/zed'K/img/EN.png "English"  
[BR]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/zed'K/img/BR.png "Português Brasil"
[CN]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/zed'K/img/CH.png "中文"  
[DE]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/zed'K/img/DE.png "Deutsch"  
[ES]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/zed'K/img/ES.png "Español"  
[FR]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/zed'K/img/FR.png "Français"  
[IT]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/zed'K/img/IT.png "Italiano"  
[JA]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/zed'K/img/JA.png "日本語"  
[KO]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/zed'K/img/KO.png "한국어"  
[MX]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/zed'K/img/MX.png "Mexicano Español"  
[NL]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/zed'K/img/NL.png "Dutch"  
[NO]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/zed'K/img/NO.png "Norsk"
[PO]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/zed'K/img/PO.png "Polski"  
[RU]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/zed'K/img/RU.png "Русский"  
[SW]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/zed'K/img/SW.png "Svenska"  
[TW]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/zed'K/img/TW.png "国语"

THIS FILE: CC BY-ND 4.0 by [zer0Kerbal](https://github.com/zer0Kerbal)
  used with express permission from zer0Kerbal