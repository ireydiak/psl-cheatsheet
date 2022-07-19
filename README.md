# psl-cheatsheet
Stop Googling the same PowerShell commands and refer to this cheatsheet instead.

## How to recursively delete an entire directory with PowerShell?
Found [here](https://stackoverflow.com/questions/1752677/how-to-recursively-delete-an-entire-directory-with-powershell-2-0)
```powershell
Remove-Item -Recurse -Force some_dir
```

## Search command history
Found [here](https://serverfault.com/questions/891265/how-to-search-powershell-command-history-from-previous-sessions)
- Press `Ctrl`+`R` and then start typing, to search backward in history interactively. This matches the text from anywhere in the command line. Press Ctrl+R again to find next match.
- `Ctrl`+`S` works like above, but searches forward in history. You can use Ctrl+R/Ctrl+S to go back and forth in search results.
