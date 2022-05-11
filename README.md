<h2 align="center">
    Word Guesser Singleplayer Files
</h2>

****

> WG Singleplayer Files are good alternatives for the Multiplayer mode in
Word Guesser. If you want to play in Singleplayer simply choose a
WG-Singleplayer-File and have fun!

## Available files.
⚠️ *Currently the repository is not finished.*

|    Filename   |                         Content                                  | Version |
| -------------- | -------------------------------------------------- | -------- |
|   animals.txt  |                 Well known animals.                      |    1.1    |
| countries.txt | Big and small countries all around the world |    1.1    |
|     cities.txt   |            Capital cities around the word            |     1.0    |

## How to download?
### **Download using Word Guesser**
Start Word Guesser, select the Singleplayer mode and click Start.
Now you should see a prompt with three options. Click on 'Download'.
### **Download manually**
You can download a ZIP file with all files here: [Download](https://github.com/GregorGott/WG-Singleplayer-Files/releases/download/release/WG-Singleplayer-Files.zip)

Download a single file:
You can download a file in two ways:

📺 Terminal (wget)
1. Select the file you want to download
2. Click on 'Raw'
3. Copy the link
4. Enter the following line in your Terminal:

        wget https://path/to/file

🧭 Browser
1. Select the file you want to download
2. Click on 'Raw'
3. Right-click on 'Save as'

## How to write Singleplayer files?
Word Guesser only accept .txt files. Create a .txt file on your machine and
write every word in a new line. You can write more than one word in one line,
but Word Guesser detect it as one word with whitespace.

    Word1
    Word2
    Word3
    Word4 with some whitespaces

If you want to write a comment, write '##' at the beginning of the line.
In-line comments are not allowed.

## ✅ Allowed

    ## This is a comment.
    ## Also a comment.
    That is
    not
    a comment

Word Guesser detects three words: "That is", "not" and "a comment"


## ❌ Bad way
    Duck ## Is my favourite animal
    Pinguin ## Really nice animal
    Dinosaur ## I want to see one

Word Guesser won’t detect the comments: "Duck ## Is my favourite animal",
"Pinguin ## Really nice animal" and "Dinosaur ## I want to see one".


*That's it, simple, huh?*
