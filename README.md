Crimson-Editor-Test
===================

Issue tracking for Crimson Editor testing

Found by Halyna

Environment:
Windows 7 
Software Version:
Crimson Editor SVN263


Reproduce Steps:
Create a text file, for example, on Desktop, and name it “kuku.txt”. Put a text “i am original” on the first line of it. Close it.
Open up Crimson Editor.
Close all other files, if opened.
Create new file
Add a text in the first line “I am going to rewrite you”.
Save it as kUKU.txt file in the Desktop folder.
NO Message about rewriting the file kuku.txt.
File kUKU.txt saved.


Expected:
A message warning that  file kUKU.txt exists already in the folder.

Actual Result:
file kuku.txt is gone. kUKU.txt actually rewrote the file kuku.txt  without warning.
if  files kuku.txt and kUKU.txt handled as having the same name, message should have appeared. if not, 2 files must be saved.

Severity: High
Priority: High

Found by Halyna

Environment:
Windows 7 
Software Version:
Crimson Editor SVN263


Reproduce Steps:
Create a text file, for example, on Desktop, and name it “Text777.txt”. Put a text “i am original” on the first line of it. Close it.
Open up Crimson Editor.
Close all other files, if opened.
Create new file
Add a text in the first line “I am going to rewrite you”.
Save it as Text777.txt file on the Desktop folder.
NO Message about rewriting the file Text777.txt, that is already exists in the same folder.
File Text777.txt saved.


Expected:
A message warning that  file Text777.txt exists already in the folder and it is going to be rewritten.

Actual Result:
file Text777.txt is rewritten without warning.


Severity: High
Priority: High


Found by Halyna
Environment:
Windows 7 
Software Version:
Crimson Editor SVN263


Reproduce Steps:

Open up Crimson Editor.
Create new file
Save it by selecting “Save as...”.
See the file type as 

Expected:
list has to contain only different items.
Actual Result:
All Files item is 3 times in the list


Severity: Low
Priority: High


found by Halyna
Documentation grammar and appearance errors - folder docs

Syntaxfile.html
HEXA decimal numbers      HEX decimal numbers
explaination              explanation
prefered                  preferred
execuable                 executable
distinguishs              distinguishes
in strange way            in a strange way

preferences.html
and it's look and feel    and its look and feel
occurence                 occurrence
changable                 changeable
favorate                  favorite
milimeters                millimeters
stite                     site

about.html
print & print preview    - first item without bullet
other useful feathers - listed with "," in the end of the line

calculator.html
earler                    earlier
data functions, those are frequently used in financial problems, are now available  - seems strange for me. for you?


howtos.html
example assume ( used some times )  -  correct is "example assumes"

regexp.html
independantly             independently

lisensefile.html
licence information       license information
all right reserved        all rights reserved

severity - Low
priority - high




