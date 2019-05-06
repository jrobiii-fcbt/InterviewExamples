# Interview Examples

Example 1
```powershell
"1" + "1"
```
Example 2
```powershell
$Junk = Get-Process | where {$_.ProcessName -eq 'NOTEPAD'}
"NOTEPAD Process Id: $Junk.ProcessName"
```
Example 3
```powershell
$Junk = Get-Process
$Junk[$Junk.Count]
```

Example 4
```powershell
$Array = @(1..100)
$Array -contains (6/2)
```
