# **Simple Audio Mixer and Player**

## **Description**

This MP3 player application allows users to manage audio files across two columns, move files between columns, and control the playback and volume for each column. Users can also drag and drop files or use the file input dialog to add MP3 files to the player.

## **Features**

* Drag and drop MP3 files or use file input dialog to add audio files  
* Move audio files between Column A and Column B  
* Move audio files up, down, to the top, or to the bottom within a column  
* Global volume control for each column  
* Autoplay feature for seamless playback  
* Volume fader to adjust volume balance between Column A and Column B

## **Instructions**

### **Adding Files**

1. Drag and drop MP3 files onto the designated drop zone or click the drop zone to open the file input dialog.  
2. Files will be added to Column A by default.

### **Moving Files**

1. To move files between columns, select the checkboxes next to the files you want to move and use the "Move to Column B" or "Move to Column A" buttons.  
2. To move a file up or down within a column, select only one file at a time using the checkbox. If multiple files are selected, the system will not move any files. Use the "Move Up", "Move Down", "Move to Top", or "Move to Bottom" buttons accordingly.

### **Volume Control**

1. Use the volume sliders to adjust the volume for each column. Note that the volume setting is global for each column, meaning all audio files in that column will have the same volume level.

### **Autoplay**

1. Enable the autoplay feature for a column by checking the corresponding checkbox. When enabled, the player will automatically play the next file in the column after the current file ends.

### **Fader Control**

1. Use the fader to balance the volume between Column A and Column B. Adjusting the fader will change the volume proportionally for each column.

## **Technical Details**

* The player supports MP3 files only.  
* The volume range is from 0 to 11, where 0 is silent and 11 is the maximum volume.  
* The fader range is from 0 to 100 percent.

## **Troubleshooting**

* If files are not appearing in the columns, ensure they are MP3 files and that they are successfully loaded into the player.  
* For moving items within a column, make sure only one item is selected at a time.

## **Contributing**

Feel free to fork the repository and submit pull requests. For any issues or feature requests, please open an issue on GitHub.

