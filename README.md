# Gentor

Gentor is a utility that allows users to make their internet traffic anonymized through Tor network with minimal effort. It's easy to use and gives the user maximum control.
Acting as a transparent system proxy, DNS requests are also redirected via tor. It also disables unsafe packets exiting the system

# Installing GenTor

    wget https://github.com/ChihebBayouli/Gentor/releases/download/v0.1/setup.bin
    chmod +x setup.bin
    sudo ./setup.bin

# Quick start
To get started, simply execute gentor and follow the instructions:
    
    gentor

# Help
    OPTIONS:
      -h, --help            show this help message and exit
      -p, --privoxy         Connecting to Tor with Privoxy - Enhance your privacy
      -s, --start           Start connecting to Tor
      -x, --stop            Stop connecting to Tor
      -r, --renew           Renew the current Tor circuit
      -id COUNTRY ISO CODE  Connect to Tor exit node of a specific country
      -mac INTERFACE        Randomly change MAC address
      -c, --checkip         Check your current IPv4 address
      --dns                 Use this to fix DNS
      --nodelay             Disable delay time
      -e, --enable          Enable anonymization at boot time
      -d, --disable         Disable anonymization at boot time
      -u, --uninstall       Uninstall GenTor

## Licensing

Gentor is a closed-source program.
You can find the license for the main Gentor Program in this repo (we assume that if you are using the app you agree to the terms laid out in the license file)
