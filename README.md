# Gujarati_KaGaPa
KaGaPa phonetic layout for Gujarati keyboard

HOW TO USE?

Gujarati KaGaPa keyboard is now included in xkeyboard package. Using this only requires

```
setxkbmap in guj-kagapa
```

[[ OUTDATED OLD INSTRUCTION ]]

Xkeyboard now supports custom keymaps. So adding keymap is easy.
Just copy contents of guj_kagapa file to /usr/share/X11/xkb/symbols/custom. If custom file does not exists just create it. Done.

[[ DOUBLE OUTDATED OLD INSTRUCTION ]]
1. add contents of in_guj_kagapa file at the end of /usr/share/X11/xkb/symbols/in, you can use below command as root user
```
cat in_guj_kagapa >> /usr/share/X11/xkb/symbols/in
```
3. let your system know about this,

add this line

  ```
  guj-kagapa      in: Gujarati (KaGaPa phonetic)
```

in two files, at appropriate place, ( after line starting with "guj" ), in /usr/share/X11/xkb/rules/base.lst and /usr/share/X11/xkb/rules/evdev.lst

Restart and now you can use Gujarati KaGaPa keyboard using 
```
  setxkbmap in guj-kagapa
```

[[ END OF DOUBLE OUTDATED INSTRUCTIONS ]]

You can use Gujarati KaGaPa keyboard using
```
setxkbmap custom guj-kagapa
```
[[ END OF ALL OUTDATED INSTRUCTIONS ]]

How to type:
  characters are placed in four levels, to type level one just press the key, to type level2 use Shift+key, to type level 3 use AltGr+key, to type level 4 use AltGr+Shift+key.
  There is image file to help find characters.

You can revert back to us keyboard with
```
   setxkbmap us
```   
But don't ask me how to type that when you have activated gujarati keyboard. Have fun!!

EDIT: Ideally you should assign this setxkbmap command to keyboard, so you don't need to type them (which won't be possible anyway).
