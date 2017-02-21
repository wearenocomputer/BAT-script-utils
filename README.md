# BATStartCollection

//START NODE SERVICE
cd c:/
cd "Program files"
cd foldernamehere
node start

//START SERVICE WITH PARAMTERS
start C:\nocomputer\blackspout\BlackSpout -input 1 -mode 10 -width 640 -height 360 -x 50 -y 50 -name "Black Spout 1"


//TIME OUT
ping 127.0.0.1 -n 5 >nul

//START EXE
start C:\folder\folder\program.exe

//KILL EXE
taskkill /im program.exe /f /t

//MOUNT DRIVES
net use Z: /delete
net use Z:\\192.168.5.240\Public\camerasystem-data /u:username password /persistent:yes

