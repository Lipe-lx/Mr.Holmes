<p align="center">
  <img width="200" height="200" src="../Icon/Mr.Holmes.png">
</p>

<p align = "center">
  <img src = "https://img.shields.io/github/stars/Lucksi/Mr.Holmes">
  <img src = "https://img.shields.io/github/forks/Lucksi/Mr.Holmes">
  <img src = "https://img.shields.io/badge/Maintained%3F-yes-green.svg">
  <img src = "https://img.shields.io/github/license/Lucksi/Mr.Holmes">
  <img src = "https://img.shields.io/github/repo-size/Lucksi/Mr.Holmes">
  <img src= "https://img.shields.io/github/languages/count/Lucksi/Mr.Holmes">
  <img src = "https://visitor-badge.laobi.icu/badge?page_id=Lucksi.Mr.Holmes">
</p>

# :mag: Mr.Holmes 

### Mr.Holmes è un information gathering tool (OSINT). Il cui principale scopo è quello di ottenere informazioni riguardo a domini,username,email e numeri di telefono con l'aiuto di risorse pubbliche disponibili in rete.Utilizzando anche tecniche come i Google/Yandex dorks per ricerche ancora piu specifiche.Inoltre possono essere utilizzati dei proxy per rendere le tue richieste anonime e utilizza una WhoIs Api per avere più informazioni riguardo a un dominio.
<br>

# :heavy_exclamation_mark: DISCLAIMER
### Questo Tool non è preciso al 100% Perciò è probabile che talvolta possa fallire,Inoltre questo Tool è stato creato solo a scopo educativo e di Ricerca... usalo con responsabilità
<br>

#  SCREENSHOT
![Screenshot](../Screenshot/Screenshot.png)

<br>

<p align = "center">
<img src = "../Screenshot/Termux.png" height = "400px" width = "300px">
</p>

<br>

# :heavy_check_mark: INSTALLAZIONE LINUX/MAC:
```bash
git clone https://github.com/Lucksi/Mr.Holmes
cd Mr.Holmes
sudo chmod +x install.sh
sudo ./install.sh
```
<br>

# :heavy_check_mark: INSTALLAZIONE WINDOWS:
```bash
git clone https://github.com/Lucksi/Mr.Holmes
cd Mr.Holmes
Install.cmd
```
<br>

# :heavy_check_mark: INSTALLAZIONE TERMUX:
```bash
pkg install proot
git clone https://github.com/Lucksi/Mr.Holmes
cd Mr.Holmes
proot -0 chmod +x install_Termux.sh
./install_Termux.sh
```
<br>

#  USAGE LINUX/MAC:
    sudo python3 MrHolmes.py
    OR:
    cd Launchers
    Esegui Launcher.sh

<br>


#  USAGE TERMUX:
    python3 MrHolmes.py

<br>

#  USAGE WINDOWS:
    python MrHolmes.py
    OR:
    cd Launchers
    Esegui Win_Launcher.exe

<br>

# API KEY LINK:
    https://whois.whoisxmlapi.com
<br>

# FILE DI CONFIGURAZIONE:

    Configuration/Configuration.ini
<br>

# :heavy_exclamation_mark: ATTENZIONE
### DATABASE NON DISPONIBILE SU TERMUX
<br>

# :heavy_exclamation_mark: ATTENTION SU WINDOWS
### SE PYTHON O PHP NON SI INSTALLANO DEVI INSTALLARLI MANUALMENTE:
    
<br>

# LISTA VERSIONI:
    https://lucksi.github.io/Mr.Holmes/Pages/versions.html
<br>

# :heavy_check_mark: GUI DARK/LIGHT MODE:
```bash
cd GUI
cd Theme
edit Mode.json
write:Light=(Light-Mode)
write:Dark=(Dark-Mode) 
write:High-Contrast(High-Contrast-Mode)
write:Uchiha(Uchiha-Mode)
```
<br>

# Mode.json CODE EXAMPLE:
```json
{
    "Color": {
        "Background": "Light"
    }
}
```
<br>

# :heavy_check_mark: GUI/USERNAME/PASSWORD:
```bash
cd GUI
cd Credentials
edit Login.json
write:Status=Active/Deactive
edit Users.json
write:Username=Your Username
write:Password=Your Password
```
<br>

# Login.json CODE EXAMPLE:
```json    
{
    "Database": {
        "Status": "Active"
    }
}
```
<br>

# Users.json CODE EXAMPLE
```json
{
    "Users":[
        {
            "Username": "Your Username",
            "Password": "Your Password"
        }
    ]
}
```
<br>

# :heavy_check_mark: IMPOSTAZIONI LINGUA:
```bash
cd GUI
cd Language
edit Language.json
write:Italian
write:English 
write:François
```
<br>

# Language.json CODE EXAMPLE:
```json
{
    "Language": {
        "Preference": "English"
    }
}
```
<br>

# DEFAULT USERNAME E PASSWORD:
    Username:Admin
    Password:Qwerty123

<br>

# LINGUE DISPONIBILI:
    Italiano 🇮🇹 
    English 🏴󠁧󠁢󠁥󠁮󠁧󠁿
    Français 🇫🇷

<br>


# VERSIONE ATTUALE:
## T.G.D-1.0.2

<br>

# MAPPA INTERATTIVA REALIZZATA CON:
## Leaflet: https://leafletjs.com

<br>

# USERNAME ENTITIES:
## Le Icone sulla Cartella /GUI/Icon/Entities/Site_Icon sono state prese da: https://www.iconfinder.com/ tutti i meriti vanno ai loro rispettivi creatori

<br>

# ENCODING
## Con Questa Versione E Possibile effetuare l'Encoding dei Report

<br>

#  DECODING
## Con Questa Versione E Possibile effetuare Il Decoding dei Report

<br>

# IPOTESI
## Con Questa Versione Si Possono generare delle "Ipotesi" Basate sulle informazioni raccolte (Le Ipotesi Potrebbero non essere affidabili al 100%)

<br>

# GRAFICO:
## Con Questa nuova versione è stata aggiunta la possibilità di creare dei Grafici in ordine di schematizzare le informazioni.
# EXAMPLE:

![Screenshot](../Screenshot/Graph_Test.png)

<br>

<br>

# PDF:
## Con questa versione è possibile convertire i Grafici in PDF.

<br>

# EXAMPLE:

<p align = "center">
<img src="../Screenshot/Dark_Pdf.png" height ="400px" width = "400px" border = "5px" style="border-color:white;">
</p>

<br>

# AVAILBLE PDF-THEMES:
    Light 🌕
    Dark 🌗
    High-Contrast 🌗

<br>

# FILE-TRANSFER:
## Con questa versione è possibile trasferire i tuoi reports/PDF direttamente Sul tuo Telefono Tramite Qr-Code

<br>

# FILE-TRANSFER PAGE:

<p align = "center">
<img src="../Screenshot/File-Transfer.jpg" height ="500px" width = "300px" border = "5px" style="border-color:white;">
</p>

<br>

# :last_quarter_moon: DARK MODE:
![Screenshot](../Screenshot/Dark_Mode.png)

<br>

<p align = "center">
<img src="../Screenshot/Dark.jpg" height ="500px" width = "300px" border = "5px" style="border-color:white;">
</p>

<br>

# :full_moon: LIGHT MODE:
![Screenshot](../Screenshot/Light_Mode.png)

<br>

<p align = "center">
<img src="../Screenshot/Light.jpg" height ="500px" width = "300px" border = "5px" style="border-color:gray;">
</p>


<br>

# :last_quarter_moon: HIGH-CONTRAST MODE:
![Screenshot](../Screenshot/High-Contrast_Mode.png)

<br>

<p align = "center">
<img src="../Screenshot/High-Contrast.jpg" height ="490px" width = "300px" border = "5px" style="border-color:white;">
</p>


<br>


## <p align = center> STARGAZERS OVER TIME 


[![Stargazers over time](https://starchart.cc/Lucksi/Mr.Holmes.svg)](https://starchart.cc/Lucksi/Mr.Holmes)

<br>

## <p align= center>CREATO CON :heart: DA LUCKSI IN :it:</p>

## <p align = center>CREATORE ORIGINALE: <a href = "https://github.com/Lucksi">LUCA GAROFALO (Lucksi)</a></p>


## <p align = center>LICENZA: GPL-3.0 License <br>COPYRIGHT: (C) 2021-2023 Lucksi 
