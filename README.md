# Cisco IOS XE Commands Syntax Highlighting

<br />

<img src="assets/cisco-logo.png" alt="Cisco Logo" title="Cisco" width="300" style="display: block;"/>

<br />

> This is a fork of the original Syntax Highlighting project made by OsamaAbbas. His project can be found [here](https://github.com/Tes3awy/Cisco-IOS-XE-NotepadPlusPlus-Syntax-Highlight).

I absolutely loved the syntax highlighting provided by the original project .xml file, but I am also a big Light Mode hater. As a result, I quickly spun up this fork after I revised the original .xml file to better match my usage of Dark Mode interfaces.   

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
