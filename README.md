# US International keyboard layout

As I like to use a US keyboard (and keyboard layout) for programming, but am also a German person, I
need to use the [US international keyboard layout](https://en.wikipedia.org/wiki/British_and_American_keyboards#/media/File:KB_US-International.svg).


The so-called dead keys (~, ^, ', " and \`), which combine with letter to make characters such as à,
â, etc. usually work by first pressing the dead key and then pressing the letter key with which
you'd like to combine the accent. This is horrible when programming though, because you have to
press these dead keys twice, just to get the accent. 
Since I don't write a lot of accented letters (only German Umlaute), I wanted to make it so that
these keys don't work as dead keys by default.
On Linux, there is a keyboard layout called "US International AltGr Dead Keys", which switches up
the way those keys work in combination with AltGr. If you use this keyboard layout, the accents by
themselves appear as a usual character would after one keypress. If you use AltGr in combination
with the accent, you'd have a dead key as usual.

Now, having to use Windows sometimes, I was disappointed to not find this keyboard layout there, so
I made it myself using the [Windows Keyboard Layout Creator](https://www.microsoft.com/en-us/download/details.aspx?id=22339). 

To install it, simply download the ZIP file, extract it and run `setup.exe`. Note that you'll have
to log out and back in after installing the layout for it to work properly. You should now see a "US
International AltGr Deadkeys" layout in your input selection list.

Have fun!
