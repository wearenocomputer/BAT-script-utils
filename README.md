\\# BATStartCollection

//START NODE SERVICE <br />
cd c:/ <br />
cd "Program files" <br />
cd foldernamehere <br />
node start <br />


//START SERVICE WITH PARAMTERS <br />
start C:\nocomputer\blackspout\BlackSpout -input 1 -mode 10 -width 640 -height 360 -x 50 -y 50 -name "Black Spout 1"


//TIME OUT <br />
ping 127.0.0.1 -n 5 >nul

//START EXE <br />
start C:\folder\folder\program.exe

//KILL EXE <br />
taskkill /im program.exe /f /t

//MOUNT DRIVES <br />
net use Z: /delete <br />
net use Z: \\\192.168.5.240\Public\camerasystem-data /u:username password /persistent:yes

//DELETE HIDDEN FILES AND FOLDERS<br />
cd C:\Users\Nocomputer\Desktop\Folder<br />
del * /A:H /S /Q

