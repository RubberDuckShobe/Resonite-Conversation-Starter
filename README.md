# Neos-Conversation-Starter
Hosts files for my Neos conversation starter. **Contributions and translations are much appreciated and needed!**

## File and folder structure
The layout of the files/folders that needs to be followed in order for the in-game UI to be able to use them is as follows:

``/language_code/topic.txt``

Language codes:
- en - English
- ko - Korean
- ja - Japanese
- de - German

Examples:
```
/en/videogames.txt
/de/general.txt
```

The game randomly picks one line to display, so inside of the text files, there can be no more than one question/prompt per line, like this:

```
This line will show up in the game
This one can, too
Maybe this one, too?
And this one, of course!
```
