# garyutils
Utility API for CC: Tweaked to do various misc things. 

## To load garyutils into your project -  
First, copy the source code and paste it into a file called "garyutils"  
In a program, preferably in startup, run require("garyutils")  
Use garyutils.(insert function name here) whenever necessary  
  
## Usage -  
### padString(stringInput, desLen, dir) -  
Adds (desLen - length of stringInput) spaces to either the left or right (dir = "r" (right) or "l" (left))  
Returns the padded string  
  
### printCentered(stringInput, offset) -  
Prints stringInput centered moved to the right (offset) spaces  
  
### writeCentered(stringInput, offset) -  
Writes stringInput centered moved to the right (offset) spaces  
  
### combineTableElements(inputTable, sepChar) -  
Combines elements in a table, where they are combined based on sepChar (ex. sepChar = "/" inputTable = {"/single/","/dou","ble/","/tr","i","ple/"} becomes {"single","double","triple"})  
