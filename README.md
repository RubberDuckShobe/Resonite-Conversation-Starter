# Resonite-Conversation-Starter
Hosts files for my Resonite conversation starter.<br>
The item this code belongs to can be found in my public folder. It can also be spawned directly by pasting the following link inside of Resonite. ``resrec:///U-m1nt-/R-0988f89d-6e25-476a-9c29-3ad07630bdca``<br>
**Contributions and translations are much appreciated and needed!**

## File and folder structure:
---
The layout of the files/folders that needs to be followed in order for the in-game UI to be able to use them is as follows:

``/language_code/topic.txt``

In the case of translating UI buttons (not lines of topics), the layout needs to be as follows:

``/UI Translations/language_code.txt``

In both cases, please refer to the English template and put translated strings on the same line number as in the original.

Language codes:
- en - English
- ko - Korean
- ja - Japanese
- de - German
- nl - Dutch

> **If you would like to add a language that is not listed here, please use the language's [ISO 639-1 code](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes)!**

## Examples:
---
```
/en/videogames.txt
/de/general.txt
/UI Translations/ja.txt
/UI Translations/ko.txt
```

The game randomly picks one line to display, so inside of the text files, there can be no more than one question/prompt per line, like this:

```
This line will show up in the game.
This one can, too.
Maybe this one, too?
And this one, of course!
```
