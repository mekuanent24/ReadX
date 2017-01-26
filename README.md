# ReadX
ReadX is program pioneered to help health specalists analyze their recorded data around the globe. During my attendance at the AngelHack Hackathon a health organization called Doctos Without Boarders needed a software that can search words phonetically from their data. When their doctors record names around the world, similar names are inputted with different spellings. They needed to be able to search for one form of a name so that all the similar names pop-up in their search. ReadX will allow you to upload your own excel sheet so you can search for a word via how it sounds. Then you'll be able to search for a name and ReadX will output a list of words that are spelled differently but are the same name.  

PLEASE INSTALL JEXCEL API FROM HERE BEFORE RUNNING THE PROGRAM
  https://sourceforge.net/projects/jexcelapi/files/jexcelapi/2.6.12/

1. Change the directory in the 'List' class to point to your own excel sheet
2. The program is made to automatically detect the keywords 'NAME' and 'ALT_NAME' in the first row of the excel sheet so you'll need your names to be under those columns. You can change the keyword for the column with the list of names in the 'List' method
3. Run the program and it should ask to search for a word
4. It will output a list of words that are spelled verbatim compared to your search or any similar words
