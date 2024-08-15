# CybTCP_Sniffer

## Overview
CybTCP_Sniffer is a basic network sniffer designed to capture and analyze TCP packets. This tool helps network administrators and security professionals monitor network traffic and diagnose network issues.

## Features

__Packet Capture:__ Captures TCP packets on specified network interfaces.

__Real-time Analysis:__ Analyzes and displays packet details in real-time.

__Logging:__ Saves captured packets to log files for further analysis.

## Installation Instructions

 __Clone the Repository:__
 
>git clone https://github.com/yourusername/CybTCP_Sniffer.git

>__cd CybTCP_Sniffer__


 ## Install Dependencies:
  
  >pip install scapy


  ## Usage

  >python3 CybTCP_Sniffer.py < interface > verbose
>
  _Replace <interface> with the name of the network interface you want to sniff packets on (e.g., eth0, wlan0, etc.)._
 _action may require root priveledges_

 __This will start the packet sniffer, logging packet information to a file and also printing it to the console.__

## Dependencies

Python 3.x

Scapy

## Structure

__CybTCP_Sniffer.py:__ Main script for running the sniffer.

__dependencies:__ scapy

__sniffer_eth0_log.txt:__ where log files are stored.


### For any questions or suggestions, feel free to open an issue or contact me at mrkusimm@gmail.com
  

