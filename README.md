Sperry Wallet 0.8 BETA

Copyright (c) 2015-2018 Sperry Tecnologia

Distributed under the MIT/X11 software license, see the accompanying
file COPYING or http://www.opensource.org/licenses/mit-license.php.
This product includes software developed by the OpenSSL Project for use in
the OpenSSL Toolkit (http://www.openssl.org/).  This product includes
cryptographic software written by Eric Young (eay@cryptsoft.com).


Intro
-----
Sperry is a free open source peer-to-peer electronic cash system that is
completely decentralized, without the need for a central server or trusted
parties.  Users hold the crypto keys to their own money and transact directly
with each other, with the help of a P2P network to check for double-spending.


Setup
-----
Unpack the files into a directory and run sperry-qt.exe.

Sperry-Qt is the original Sperry client and it builds the backbone of the network.
However, it downloads and stores the entire history of Sperry transactions;
depending on the speed of your computer and network connection, the synchronization
process can take anywhere from a few hours to a day or more.

Download
-----

Windows Installer Wallet:  https://github.com/iluysperry/Wallet-Sperry-Coin/raw/master/sperry-0.8.7.5-win32-setup.exe

Windows Portable Wallet :  https://github.com/iluysperry/Wallet-Sperry-Coin/raw/master/sperry-qt.exe


After running the wallet, wait to synchronize...


Local files windows
-----

Default Location

Go to Start -> Run (or press WinKey+R) and run this:

    %APPDATA%\Sperry

Sperry data folder will open. 

For most users, this is the following locations, just change username:

C:\Documents and Settings\YourUserName\Application data\Sperry

C:\Users\YourUserName\Appdata\Roaming\Sperry 

Wallet backup 
-----
Just copy and save wallet.dat file put in a safe location. 

When you need to restore a new wallet just copy the file and overwrite it in the same directory as described.
