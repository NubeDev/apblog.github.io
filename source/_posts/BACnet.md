---
title: BACnet On A Raspberry PI...
date: 2017-01-26 20:56:55
tags: BACnet Raspberry PI

---
# Setup for BACnet on a Raspberry PI


### Step 1
Install bacnet on raspberry PI

https://sourceforge.net/projects/bacnet/files/bacnet-stack/bacnet-stack-0.7.5/

### Step 2

Using the stock Raspbian image, log in as ‘pi’ and execute these steps…
*must be ssh into PI*

```
tar xvfz bacnet-stack-0.7.1.tgz
cd bacnet-stack-0.7.1
make clean all
```
This should build all the demo binaries – takes a few minutes. Then you can run up your RaspberryPi as a BACnet server using the defaults by typing..

## Step 3
Start the BACnet Server

```
bin/bacserv
```

## Step 4
Install tools for testing BACnet Server
https://www.ccontrols.com/sd/bdt.htm
