
# Preparazione
1. Installare Open SSH su Windows
Apreire Powershell e eseguire il comando
```
  # Install ssh client from PowerShell
  PS C:\> Add-WindowsCapability -Online -Name OpenSSH.Client*
```
2. Installare Windows Terminal da qui https://aka.ms/terminal
3. Aprire Windows Terminal
4. Preparare Raspberry PI e configurare
DA FARE
# Collegarsi a Raspberry
1. Aprire Windows Terminal
Digitare
```
c:\> ssh pi@raspberry.local
```
Yes
[Impostare la pasword]
# Installare Kiauh
Nella sessione ssh scrivere questi 4 comandi
```
  cd ~
  sudo apt-get install git -y
  [password]
  git clone https://github.com/th33xitus/kiauh.git
  ./kiauh/kiauh.sh
  
```
# Installare klipper, Fluidd, Mainsail con kiauh
Selezionare opzione 1 - Install

