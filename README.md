#  Scripts

## bookread

* Script to read books from different topics.
* Launches from dmenu
* First selects topic from user
* After shows booklist for that topic

## configedit

* Scipt to edit config of various programs
* Uses dmenu to select an program to edit that programs config file

## mansplain

* Lists out all the manual files in the system
* Uses dmenu to show the list
* Opens the selected manual file in zathura

## websearch

* Easily searches in any search engine specified in the script
* Uses dmenu to list the engines
* After selecting an enginer, an exmpty dmenu prompt will ask for query

## setbg

* Changes background
* With no arguements it will set a random wallpaper from the default wallpaper folder
* Given a file name, it will set that as a wallpaper
* Given a directory, it will set a image from that directory randomly
* Genrates colorschemesusing pywal

## dmenuemoji

* Copy emojis from dmenu
* Reads from a file that has all the emojis listed
* has issues in showing the emoji in dmenu. (In arch, installing `libxft-bgra` package from aur solves the issue

## prompt

* Gives a prompt to user to select either yes or no
* If user selects yes then it runs the command specified in the argument
