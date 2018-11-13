# Cara Remote Desktop Windows Melalui LAN

## Pada komputer yang ingin di-remote

Siapkan Catatan untuk mencatat :
* $Computer-Name => langkah 1 
* $User-name     => start menu
* $IPv4 Address  => cmd:ipconfig [Wireless LAN Adapter Wi-fi]
* $Password (?) harus ada password pada komputer

1. Windows Explorer > This PC/My Computer > Properties
2. Advanced system settings
3. Tab Remote : centang 
    * Allow Remote Assistance connections to this computer 
    * Allow remote connections to this computer
    Klik OK


## Pada komputer yang ingin meng-remote

1. run:MSTSC 
2. Remote Desktop Connection > Show Options
3. Isikan :
    * Computer  =>   $IPv4 Address
    * User Name =>   $Computer-name\$User-name
    Connect
4. Isikan password (Dialog Enter your credentials)
5. Yes             (Dialog The identity of the remote cannot be verified.)
6. Done