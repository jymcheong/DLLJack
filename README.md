# DLLJack
DLL Hijacks in common applications rolled into quick persistence with powershell

Tested on Windows 10  
Current Supported Apps: OneDrive, Dropbox, Discord, Flux, Foxit Reader, HipChat, Audacity and Spotify

## Usage
Your dll needs to be present on the system prior to using DLLJack. During usage your dll will be copied and placed into specifations dependendent on application choices.  
DLLJack is the main function.  
CleanHijacks removes all persistence.

## Examples
DLLJack -Appname Onedrive -DLLPath c:\payload.dll  
CleanHijacks

## ToDo
More applications  
Add Com Hijacks
