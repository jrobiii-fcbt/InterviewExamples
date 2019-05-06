# Interview Examples

Example Number 1
```powershell
"1" + "1"
```
Example Number 2
```powershell
$Junk = Get-Process | where {$_.ProcessName -eq 'NOTEPAD'}
"NOTEPAD Process Id: $Junk.ProcessName"
```
Example Number 3
```powershell
$Junk = Get-Process
$Junk[$Junk.Count]
```
