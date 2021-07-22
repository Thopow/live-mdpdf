# Document creation with Live-MDPDF

This small script let you create Documents without a Word-Processor and monitor the output at the same time. 

---

## Use of the script

### Dependencies
- zathura PDF viewer (To update the previewe on save)
- inotify
- Text Editor

### Install
Just copy or link the script live-mdpdf to your ${PATH} directory.

### Use

`$ live-mdpdf file.md output.pdf`

If you don't give an argument, `$ live-mdpdf`, your editor will ask you for a file name at your first save. 
If output file is not given, the script will default to "file.md.pdf"

---
