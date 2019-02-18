## Add `cmd` into conext menu
```bat
Windows Registry Editor Version 5.00
[HKEY_CLASSES_ROOT\Directory\shell\CommandPrompt]
@=”Command Prompt:”
[HKEY_CLASSES_ROOT\Directory\shell\CommandPrompt\Command]
@=”cmd.exe /k cd %1″
Windows Registry Editor Version 5.00
[HKEY_CLASSES_ROOT\Directory\Background\shell\CommandPrompt]
@=”Command Prompt:”
[HKEY_CLASSES_ROOT\Directory\Background\shell\CommandPrompt\Command]
@=”cmd.exe /k cd %1″
```
