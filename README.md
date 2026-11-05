# Ascii-Sharks-Bg
Ascii Sharks as a animated wallpaper! 

Use this command to deploy:
cd $HOME\Downloads
Expand-Archive .\ascii-sharks-wallpaper.zip -DestinationPath . -Force
Get-ChildItem .\ascii-sharks-wallpaper -Recurse | Unblock-File
powershell -NoProfile -ExecutionPolicy Bypass -File .\ascii-sharks-wallpaper\Install-SharkWallpaper.ps1 -Startup

And this to stop:
& "$env:LOCALAPPDATA\AsciiSharks\Stop-SharkWallpaper.ps1" -RemoveStartup
