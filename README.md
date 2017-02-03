# Tor-Pi-do-V-1-0-1
Tor-Pi-do version: 1.0.1 
Welcome to TOR-Pi-do Version 1.0.1 for the Raspberry Pi 3 

By: H0m3l3ss Hacker 

Tor-Pi-do is based on a Debian Jessie (lite) build, XFCE, and custom icons by jmsoviet. 

Tor-Pi-do is configured to use TOR anonymity with Firefox. TOR has not come up with a browser for ARMHF architecture.

To start Tor:

pi@Tor-Pi-do:~ $ sudo service tor start

Check to verify that Tor is running:

pi@Tor-Pi-do:~ $ sudo service tor status

You can check Tor setup: https://check.torproject.org/

Firefox has been setup as a Tor browser. What does that mean? The settings for Firefox have been changed, and privacy add-ons have been added. 

Preferences --> General --> Home Page --> https://3g2upl4pq6kufc4m.onion
  (DuckDuckGo onion page.)

Preferences --> Search --> Default Search Engine --> DuckDuckGo
  (One-click search engines --> Debian packages and DuckDuckGo, not recomended to use.)

Preferences --> Privacy --> History --> Never remember history

Preferences --> Data Choices --> Disabled Crash Report 

Preferences --> Settings --> Manual proxy configuration --> SOCKS Host: 127.0.0.1 Port: 9050 SOCKS v5 Remote DNS
  (Removed all from 'No Proxy for:' )


There have also been five Add-ons added:

Privay Badger - https://www.eff.org/privacybadger - "Privacy Badger blocks spying ads and invisable trackers."

HTTPS Evererywhere - https://www.eff.org/https-everywhere - "HTTPS Everywhere is produced as a collaboration between The Tor Project and the Electronic Frontier Foundation."

uMatrix - https://github.com/gorhill/uMatrix - "A point-and-click matrix-based firewall, with many privacy-enhancing tools. uMatrix put you in full control of where your browser is allowed to connect, what type of data it is allowed to download, and what it is allowed to execute. Nobody else decides for you: You choose. You are in full control of your privacy."

uBlock Origin - https://github.com/gorhill/uBlock#ublock-origin - "An efficient blocker: easy on memory and CPU footprint, and yet can load and enforce thousands more filters than other popular blockers out there. Flexible, it's more than an "ad blocker": it can also read and create filters from hosts files."

NoScript - https://noscript.net - "Extra protection for your Firefox: NoScript allows JavaScript, Java (and other plugins) only for trusted domains of your choice (e.g. your home-banking web site). This whitelist based pre-emptive blocking approach  prevents exploitation of security vulnerabilities (known and even unknown!) with no loss of functionality... Experts will agree: Firefox is really safer with NoScript :-)"

Network manager - wicd - http://wicd.sourceforge.net/
" Wicd is an open source wired and wireless network manager for Linux which aims to provide a simple interface to connect to networks with a wide variety of settings.

Some of Wicd's features include:

    A full-featured interactive console interface and graphical interface
    No required graphical dependencies (ie, no X, Gnome, KDE)
    GTK interface has no GNOME dependencies, so it can be used in XFCE,      Fluxbox, Openbox, Enlightenment, etc.
    Ability to connect to wired (Ethernet only, no PPPoE/DSL support yet) and wireless networks
    Profiles for each wireless network and wired network
    Many encryption schemes, some of which include WEP/WPA/WPA2 (and you can add your own)
    Remains compatible with wireless-tools
    Tray icon showing network activity and signal strength "


This is an open-source project. Please feel free to make it better!

Special thanks: 

Jimmy2x - Brother without your support this may have never happened. Your patience, kindness, and help will not be forgoten. "Build it again..." 

Thanks:

EB
legion 303
Telecon
th3R0s3
KT
TheSpaniard - "I for one welcome our monkey-driven tank overlords"
ShortRound
