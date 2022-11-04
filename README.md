# Scitalda, write and play music with Alda via ScitE
This plugin allow you to use Scintilla Text Editor (ScitE) for writing Alda music scores and play immediately inside it.
Alda is a text-based programming language for music composition. It allows you to write and play back music using only a text editor and the command line.
website: www.alda.io
Actually this is an alpha version, but it works correctly. I tested on Windows, not sure wich it works on other platforms. It provides some sintax color highlighting, but for some command.
I hope that someone would improve this plugin for future.

# Steps to use:
I assumed wich you have installed Alda on your pc and followed all instructions to set path for use.
* 1. download scite from www.scintilla.org
* 2. Download alda.properties from this repository.
* 3. Unzip the wscite.zip file and store alda.properties in its folder.
* 4. Create a blanc alda file (For example test.alda) and open with ScitE.
* 5. Write this:
piano:
  o5 c d e c c d e c e f g e f g
 * 6. Save file with Ctrl+S, then press F5. If all it's ok, it will play and you hear your music just created.
