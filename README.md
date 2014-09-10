wialon-ios-gps-tag-lang
=======================

To create a strings file manually, create a new file in TextEdit (or your preferred text-editing application) and save it using the Unicode UTF-16 encoding. (When saving files, TextEdit usually chooses an appropriate encoding by default. To force a specific encoding, you must change the save options in the application preferences.) The contents of this file consists of a set of key-value pairs along with optional comments describing the purpose of each key-value pair. Key and value strings are separated by an equal sign, and the entire entry must be terminated with a semicolon character. By convention, comments are enclosed inside C-style comment delimiters (/* and */) and are placed immediately before the entry they describe.

Example:
Strings localized for English
```  objc
/* Menu item to make the current document plain text */
"Make Plain Text" = "Make Plain Text";
/* Menu item to make the current document rich text */
"Make Rich Text" = "Make Rich Text";


```

 Strings localized for German
```  objc
/* Menu item to make the current document plain text */
"Make Plain Text" = "In reinen Text umwandeln";
/* Menu item to make the current document rich text */
"Make Rich Text" = "In formatierten Text umwandeln";
```
