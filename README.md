# # Task Five: Metasploitable Nmap Scan

This repository contains the results of an Nmap scan on a Metasploitable machine with IP `10.0.2.4`.

## Overview

The goal of this task is to identify open ports and services running on the Metasploitable machine using Nmap, a powerful network scanning tool. The scan results are saved and documented for further analysis.

## Nmap Command Explanation

The following Nmap command was used to perform a detailed scan:

```bash
sudo nmap -n -p- -sV 10.0.2.4 -oN portscan.txt

## Command Breakdown:
sudo: Run the commands with superuser privileges.
nmap: The network scanning tool.
-n: Disables DNS resolution to speed up the scan.
-p-: Scans all 65,535 TCP ports.
-sV: Detects the version of services running on open ports.
10.0.2.4: The target IP address of the Metasploitable machine.
-oN portscan.txt: Saves the output to portscan.txt.

##Files

portscan.txt: Contains the results of the Nmap scan. This file lists all open ports and its services and versions found on the target machine.
