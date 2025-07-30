# Super Mario Construct Translations Hub

Hello and welcome to the translation repository of Super Mario Construct!
In this repository, you can contribute to translating Super Mario Construct to make the editor more accessible to people around the world.

In case you'd like to contribute, be sure to give the information below a read, as it includes important information.

## Available in-game languages
Below are the languages that have significantly enough translated strings to be in-game, but remember that they are still worthy maintaining due to new strings being added after a large SMC update!  
• _English (North America)_  
• _English (Brittain)_  
• _German / Deutsch_  
• _Dutch / Nederlands_  
• _French / Français_  
• _Spanish / Español_  
• _Portuguese / Português_  
• _Italian / Italiano_  
• _Polish / Polski_  
• _Russian / Русский_  
• _Japanese / 日本語_  
• _Latin / Latina_  

## Currently work-in-progress languages
These are the languages that have WIP translations, but are not yet ready to be in the game.  
(None at the moment.)

## General Rule of Thumb
• Do not use Google Translate to localize the text/strings. Google Translate is not always accurate and does not know context.  
• Please only contribute to translations if you have at least a moderate understanding of the target language.  
• Do not insert any foul language (anything that is considered inappropriate) into the translation files.  
• Avoid translated strings removing or inserting new information.  
• Variations of the same language (e.g. American vs. British English) are often allowed, but please consult us first to make sure.  
We aim for people to take the localization process seriously and in good faith, any violation of these rules could lead to a suspension from contributing to this repository.

## Guide on translating - important info!
If you'd like to help translate the game into your native language, you're at the right place!
Open up one of the available translation files and you can help translate 'strings'. Strings are simply a word, a sentence, or a paragraph of text.
### The translation file
In a translation file, you'll see the translation keys on the left - don't touch these! You want to translate the strings on the right side of the file.  
This is what you'll see when you open a translation file:
![image](https://github.com/Level-Share-Square/SMC-translations/assets/31360023/5d2b7854-32fb-4944-b374-10b02c22ffc0)
### What are these {0} things doing in here!?
Sometimes, you may encounter {0} in translation strings. These are simply replaced by a word or number in the game itself - it allows lines to be re-used without needing to be re-translated. You can move the {0} around freely in a sentence to have it make grammatical sense.
### Time notation
In English, the past dates are notated as e.g. '7 days, 9 hours ago'. If the 'ago' part comes at the start of the sentence in your language, go to 'common -> time > notation' and update {0} {1} to {1} {0}.

## How to start translating
1. Go to https://github.com/Level-Share-Square/SMC-translations/fork
2. Then, in your forked repository, press the **Add file** button at the top.
3. Visit [this link](https://www.ibm.com/docs/en/rational-soft-arch/9.7.0?topic=overview-locales-code-pages-supported) and find your language code, then name the file after that (e.g. if the language code is en-UK, name it **en-UK.json**)
4. Copy the contests of [the en-US language file](https://github.com/Level-Share-Square/SMC-translations/blob/main/en-US.json) over to the new file.
5. Translating can ensue!

## How to submit your translation file
In your forked repository, press **Pull requests** at the top-left, and then **New pull request** (the green button). Then press 'Create pull request'.

PS: It's fine to make a pull request even if you haven't finished translations yet, just be sure to mention the WIP status in the description of the pull request.

## Translation FAQ
### When will work-in-progress translations appear in-game?
WIP-translations need to have a significant amount of strings translated in order to qualify going in-game, preferably at least 85-90% of strings.  
Once languages have reached this threshold, they then go through a vetting process, which may still take some time, but after that they'll be ready to appear in-game.
### Where can I find localized versions of sprite names?
[Mariowiki](https://mariowiki.com) is a great resource for finding localized names of sprites, such as the Goomba being called Kuribo in Japanese. Not all sprites have a localized name though, typically you can simply leave these in English.
### Where can I ask more questions?
Feel free to [contact us](https://levelsharesquare.com/contact) over at Level Share Square or [create a new Issue](https://github.com/Level-Share-Square/SMC-translations/issues) with your question, and we'd be happy to help out and answer it!

