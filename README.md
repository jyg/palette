# palette
![image](https://github.com/user-attachments/assets/33e8d785-f032-4010-ad88-4fbe3aeb2565)

A 2 levels dropdown menu inspired by plugdata's palette

## Goal
enable menus for dynamic creation of objects inside a patch

## Requirements
* puredata vanilla + iemguts **or** else lib
  **or**
* plugdata nightly build 21-10-24 01:21 UTC	88aff89  or newer
  
## Usage
* Copy palette folder into externals folder or any other place pd/plugdata will search for.
* Create an object [palette <catalog>) in your patch. <catalog> is a xml file containing all items that your palette will contain. For example,  **.palettes_test_4**  in plugdata user folder.
