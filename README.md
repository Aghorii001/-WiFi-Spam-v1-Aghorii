# -WiFi-Spam-v1-Aghorii
    This script allows you to generate the number of SSIDs that you want, unless you're using the default word list (1000 SSIDs).

    If you are going to use the 4th option I recommend you generate up to ~5000 SSIDs

    Some Intel® Hardware In particular Centrino are known to cause problems becuase of the way mdk3 works.
        From the mdk3 documentaion: MDK3 uses the drivers and Injection routines from this project and its predecessor. Thus, all drivers listed there should work with MDK3. (Some special hardware, like Intel Centrino (ipw2200) is NOT supported since they can only inject data, and no management information!)

Dependencies

MDK3 sudo apt-get install mdk3: https://github.com/wi-fi-analyzer/mdk3-master

MACCHANGER sudo apt-get install macchanger https://github.com/alobbs/macchanger

PWGEN sudo apt-get install pwgen

    Dependencie installation for Arch Linux: sudo pacman -S mdk3 macchanger pwgen

Instalation and usage

    Download the files git clone https://github.com/Aghorii001/-WiFi-Spam-v1-Aghorii.git

    Dependencie instalation

2.1 Method 1 run the install.sh file AS ROOT

2.2 Method 2 Manualy add sources and install packages listed above

    Run the script sudo WiFiSpam.sh

Disclaimer

This project is for testing and educational purposes. Use it only against your own networks and devices. I don't take any responsibility for what you do with this program.
