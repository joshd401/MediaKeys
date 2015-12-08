MediaKeys
=======
# Description
This script sends Windows media key event to the system based on first parameter to the script that gets looked up in
a dictionary and mapped to an appropriate command

It is a python script, so you have to have Python3 installed

# Usage
I use it by having created following shortcuts (.lnk) in my system path

location of the item                                                        name
"C:\Python34\python.exe c:\projects\personal\MediaKeys\MediaKeys.py p"      p
"C:\Python34\python.exe c:\projects\personal\MediaKeys\MediaKeys.py n"      n
"C:\Python34\python.exe c:\projects\personal\MediaKeys\MediaKeys.py pp"     pp
"C:\Python34\python.exe c:\projects\personal\MediaKeys\MediaKeys.py u"      u
"C:\Python34\python.exe c:\projects\personal\MediaKeys\MediaKeys.py d"      d

Now I can control music from my non Media Key enabled keyboard by:
To play/pause
Win+r, p, Enter 

To move to next song
Win+r, n, Enter

To move to previous/beginning of song
Win+r, pp, Enter

Volume Up/Down the same with u & d,

to repeat the command, just do: Win+r, Enter
I use it with MS Groove music, but is should work with any decent media player

# License
This is pretty much all taken from http://stackoverflow.com/questions/11906925/python-simulate-keydown (Noctis Skytower)
