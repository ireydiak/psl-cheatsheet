# psl-cheatsheet
Stop Googling the same PowerShell commands and refer to this cheatsheet instead.

## How to recursively delete an entire directory with PowerShell?
Found [here](https://stackoverflow.com/questions/1752677/how-to-recursively-delete-an-entire-directory-with-powershell-2-0)
```powershell
Remove-Item -Recurse -Force some_dir
```
