# Gujarati_KaGaPa
KaGaPa phonetic layout for Gujarati keyboard

HOW TO USE?

1. add contents of in_guj_kagapa file at the end of /usr/share/X11/xkb/symbols/in
2. let your system know about this,

add this line

  guj-kagapa      in: Gujarati (KaGaPa phonetic)

in two files, at appropriate place, ( after line starting with "guj" ), in /usr/share/X11/xkb/rules/base.lst and /usr/share/X11/xkb/rules/evdev.lst

Restart and now you can use Gujarati KaGaPa keyboard using 

  setxkbmap in guj-kagapa

You can revert back to us keyboard with

   setxkbmap us
   
But don't ask me how to type that when you have activated gujarati keyboard. Have fun!!
