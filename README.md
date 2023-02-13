# Attendence-System-Using-Bar-Code

This project is for attendence system uses students ID card in which there is barcode behind the ID card which once scanned to the camera take a unique ID called as "PRN" 
and saves it in a Dataframe and later is saved to a csv file so teachers can have an additional copy of the csv file in their desktop.

After we made a dataframe with dates of classes where students attended class, we now calculated the attendence percentage of each student

And we can also find how much attendence percentage the given student is having. (and displays if it is above 75% or not.)

And a graph is also displayed displaying the attendence percentage of each student in the class.


To make the over all programs efficient; lets say camera runs into an error and now the question is what about the scanned PRN? so its really simple... As soon as camera scans any ID it stores in another csv file barcode_Data.csv so just incase if the particular students ID is not scanned we can check in this csv just to make sure any prn is not forgetten to be appended.
