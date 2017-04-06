# StatusBarExtended

Extends the status bar in fman to show additional information.

Turn the plugin on or off by using the keyboard shortcut, default is **F3**.



**Features**

Adds extra information to the status bar.

- Show number of directories and files/size in current directory for both panes
- Show "Toggle hidden files" status
- Show directories and files/size when selecting files




**Preview**

![Screenshot Win 10 v0.3.0](fman-plugin-statusbarextended-v0.3.0.png)



**Changelog**

**v0.1.1 - 06.04.2017:**

- Show binary prefix instead of decimal for file size

**v0.1.0 - 01.03.2017:**

- Shows output only for the currently active pane due to layout/resize issues 
- Don't display "Files: n" and "Size: n xB" if there are 0 files in current directory
- Hidden status is visualized by checkmark or cross


**25.02.2017:**

- Align text to the left and right for the respective panes
- Reduce text to make the status bar smaller thus allowing resizing window smaller


**19.01.2017:**

- Shows selected directores and files/filesize when selecting files
- Restructured code for readability


**16.01.2017:**

- StatusBar shows immediately when toggled


**28.11.2016:**

- Cleaned code
- Should work in all 3 supported OS (tested on Windows and Linux only)
