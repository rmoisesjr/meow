# Meow - Hack The Box Walkthrough for Beginners

## Introduction
"Meow" is a fun beginner-friendly machine on Hack The Box. The goal is to find your way into the system and get the secret "flags."

## Prerequisites
- Have an account on Hack The Box.
- Connect to the Hack The Box VPN.

## Steps
1. Connect to the VPN provided by Hack The Box.
2. Once connected, visit the Hack The Box website and navigate to the "Meow" machine.
3. Click on the spawn machine button to obtain the machine's IP address.
4. Use a port scanning tool like Nmap to scan the machine for open ports and services.
5. Type the following command in the terminal: **nmap -sC -sV -v [IP ADDRESS]**
6. Port number 23 (telnet) should be open.
7. Now you can connect to the target machine using the machine's IP discovered earlier.
8. Once you are in, you can become root by simply typing `root`, and you will know you are root because you won't have the `#` symbol after your username.
9. Search the directory to find a flag.
10. When you find the flag, you will have successfully completed the Meow machine.
