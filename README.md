# Arabic Phonetic Keyboard Layout by Talha Waheed

## Instructions:

1. Place the file named 'arph' in the directory /usr/share/X11/xkb/symbols
2. Open /usr/share/X11/xkb/rules/evdev.xml and append the following code to the 'layoutList' tag:
```<layout>
   <configItem>
      <name>arph</name>
      <shortDescription>arph</shortDescription>
      <description>Arabic (Phonetic Talha)</description>
      <languageList>
         <iso639Id>ara</iso639Id>
      </languageList>
   </configItem>
   <variantList/>
</layout>```
