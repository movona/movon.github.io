## Add `cmd` into conext menu
Copy and save the snippts as cmd.reg:
```bat
Windows Registry Editor Version 5.00
[HKEY_CLASSES_ROOT\Directory\shell\CommandPrompt]
@=”Command Prompt:”
[HKEY_CLASSES_ROOT\Directory\shell\CommandPrompt\command]
@=”cmd.exe /K cd %V″
Windows Registry Editor Version 5.00
[HKEY_CLASSES_ROOT\Directory\Background\shell\CommandPrompt]
@=”Command Prompt:”
[HKEY_CLASSES_ROOT\Directory\Background\shell\CommandPrompt\command]
@=”cmd.exe /K cd %V″
```
Double click to execute cmd.reg
