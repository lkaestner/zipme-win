# zipme-win
Tiny BAT script which zips the contents of the directory, the script is located in.

# Prerequisites
- requires 7zip installed and on the PATH

# Usage
- Suppose you want to backup the directory "C:/my/dir".
- You place "zipme.bat" in that directory and run it via double-click.
- The script will create a ZIP file like "backup_2020-12-31_23-59-59.zip" (format: yyyy-MM-dd_HH-mm-ss).
- There are no command-line parameters.
- Any ZIP files already present in the directory will not be included in the newly created archive.
