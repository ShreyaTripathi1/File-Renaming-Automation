# File-Renaming-Automation
This repository demonstrates how to automate renaming multiple files using Excel and PowerShell. This method is especially useful when working with large datasets, where manually renaming files would be time-consuming and prone to error. 

The task involved renaming over 100 video files with long and complex names to a more systematic format to prepare custom dataset. This method can be applied to any similar situation where files need to be renamed sequentially or according to a pattern.

## Why Automate Renaming?

When working with custom datasets or large batches of files, manual renaming can:
- Be **time-consuming** when there are many files.
- Lead to **errors** due to typos or inconsistency in naming.
- Slow down **productivity** and disrupt workflows.

By using **Excel** to structure the renaming pattern and **PowerShell** to automate the process, you can save time and ensure consistent file names.

## Requirements
- **PowerShell**
- **Excel**
- **Files** you want to rename in a folder
- **Notepad**


## Steps to follow:
1. Generate a list of files using PowerShell: `dir -Name > filelist.txt`
2. Use Excel to generate renaming commands.
3. Run the batch file to rename the files sequentially.

For detailed steps, check the document.
