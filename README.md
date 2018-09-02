# Autoinstall  Masternode Planetpay VPS Ubuntu 16.04

Open up an SSH client (Putty) then Register & Log in to your VPS as root. Ubuntu(16.04) VPS is recommended.
```
wget https://raw.githubusercontent.com/PlanetPay/Tools/master/autoinstall.sh
```
```
chmod 755 autoinstall.sh
```
```
./autoinstall.sh
```

# WIN WALLET

Send 3000 PLT to the MN_ADDRESS
Open Debug console.
In the debug console command box enter the:
```
masternode genkey
```
```
masternode outputs
```

Edit masternode.conf file.

Find your masternode.conf file:

c:\Users\username\AppData\Roaming\Planetpay (windows)

Open masternode.conf with Notepad

Format your masternode information:

MASTERNODE_ALIAS_NAME VPS_IP:13127 MN_GENKEY TX_ID TX_INDE
