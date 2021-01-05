## Arabic Phonetic Keyboard Layout by Talha Waheed

#### Usage instructions:

1. Place the file named 'arph' in the directory /usr/share/X11/xkb/symbols
1. Open /usr/share/X11/xkb/rules/evdev.xml and append the following code to the 'layoutList' tag:
   ```
   <layout>
      <configItem>
         <name>arph</name>
         <shortDescription>arph</shortDescription>
         <description>Arabic (Phonetic Talha)</description>
         <languageList>
            <iso639Id>ara</iso639Id>
         </languageList>
      </configItem>
      <variantList/>
   </layout>
1. Go to Settings>Region & Language>Input Sources and add 'Arabic (Phonetic Talha)'. 
1. Restart Ubuntu
1. استمتع

#### Working checked on:
Ubuntu 16.04, 18.04 and 20.04.

#### Special Mentions:
- Custom Keyboard in Linux/X11 by Daniel Paul O'Donnell [http://people.uleth.ca/~daniel.odonnell/Blog/custom-keyboard-in-linuxx11]<br>
- Layout inspired by 'KBD AraPhon' [http://arabic.omaralzabir.com/home]
