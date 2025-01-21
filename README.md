# Cisco IOS XE Commands Syntax Highlighting for Dark Mode in Notepad++ 

<br />

<img src="assets/cisco-logo.png" alt="Cisco Logo" title="Cisco" width="300" style="display: block;"/>

<br />

> This is a fork of the original Syntax Highlighting project made by OsamaAbbas. I only reskinned it. His project can be found [here](https://github.com/Tes3awy/Cisco-IOS-XE-NotepadPlusPlus-Syntax-Highlight).

I absolutely loved the syntax highlighting provided by the original project .xml file, but I heavily dislike Light Mode in any application (It's too harsh on the eyes! lol.) As a result, I quickly spun up this fork after I revised/reskinned the original .xml file to better match my usage of Dark Mode interfaces.

## Revised setup instructions from the original project:
After Installing [NotePad++](https://notepad-plus-plus.org/downloads/), place the `Cisco_IOS_XE_Dark_Mode_byMicahKezar.udl.xml` file within the `%AppData%\Notepad++\userDefineLangs` folder, and restart NotePad++.

Files with extensions `.cisco`, `.ios`, `.xe`, `.log`, `.txt`, `.conf`, and `.config` will automagically use this new UDL as their default language when opened with NotePad++. Remove or add any extension when desired.

To change this behavior:

1. Open the `Cisco_IOS_XE_Dark_Mode_byMicahKezar.udl.xml` file.
2. For example, remove `txt` from the `ext` property in `<UserLang>`.

```xml
<UserLang name="Cisco IOS XE" ext="cisco ios xe log conf config" udlVersion="2.0">
```

3. Save the UDL file.
4. Restart NotePad++.

## Preview

![Preview](assets/darkmodepreview.jpg)

## Specific Color Changes
The only changes I made to the original .xml was to the Hex colors. Here is the Diff Checker:
![{59B33364-5FF7-4297-9D44-8DC03D3D852E}](https://github.com/user-attachments/assets/29a6ef9f-24ce-4f10-8b36-6fb965f40e39)

By default, Notepad++ uses `#3F3F3F` as its Dark Mode background color. This was an easy enough change, but still left a minor issue. The rest of the original colors were too dark and hard to read. To remedy this, every color has been brightened to increase readability.

### If you wish to completely change the colors:

1. Open the `Cisco_IOS_XE_Dark_Mode_byMicahKezar.udl.xml` file.
2. Identify the Keyword and its matching Style you want to change (Or identify the color in specific by entering random Hex numbers [here](https://htmlcolorcodes.com/) until you find the color you were looking for).
3. Use the same tool in Step 2 to pick a new favorite color, copy the Hex #, and paste the new value into the `.xml` document. 
4. Save the document and reload Notepad++.
