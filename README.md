# Nibblecoin

## Guide to compiling Nibblecoin from source on Ubuntu
(If your on Windows just download one of the Windows binarys, no compile needed :D)

## Install depenencies

> sudo apt-get install build-essential git cmake libboost1.55-all-dev

If it wont let you install libboost, then run this command:

> sudo apt-get install libboost-all-dev

## Download the source code

> git clone https://github.com/Nibble-Coin/Nibblecoin

If you don't have git installed, download it through this command:

> sudo apt-get install git

## Get into the directory and compile

> cd Nibblecoin

> make

This will begin the compile process, which will take a while. Have a cup of tea or something while you wait.

## Go into the build directory

After it's done compiling, you need to go into the folder where the compiled builds are held

> cd build

> cd release

>cd src

## Start the simplewallet/daemon
Now just start the daemon by doing this command:

> ./nibblecoind

And after it is done syncing with the blockchain, load the simplewallet with this command

> ./simplewallet

After that your simplewallet and daemon will be fully synced! 

You can also solo mine in the daemon by doing this command: 

> start_mine [your wallet address]
