import time
import random
import string
import os
from pystyle import Colors, Colorate
import subprocess, requests
import json
from config import wallet_link_btc, wallet_link_eth, license_key
import sys
import colorama
from colorama import Fore
os.system("cls")

print(Colorate.Horizontal(Colors.purple_to_blue, """

                            ██▒   █▓▒██   ██▒    ▄████▄   ▒█████   ███▄    █   █████▒██▓  ▄████ 
                           ▓██░   █▒▒▒ █ █ ▒░   ▒██▀ ▀█  ▒██▒  ██▒ ██ ▀█   █ ▓██   ▒▓██▒ ██▒ ▀█▒
                            ▓██  █▒░░░  █   ░   ▒▓█    ▄ ▒██░  ██▒▓██  ▀█ ██▒▒████ ░▒██▒▒██░▄▄▄░
                             ▒██ █░░ ░ █ █ ▒    ▒▓▓▄ ▄██▒▒██   ██░▓██▒  ▐▌██▒░▓█▒  ░░██░░▓█  ██▓
                              ▒▀█░  ▒██▒ ▒██▒   ▒ ▓███▀ ░░ ████▓▒░▒██░   ▓██░░▒█░   ░██░░▒▓███▀▒
                              ░ ▐░  ▒▒ ░ ░▓ ░   ░ ░▒ ▒  ░░ ▒░▒░▒░ ░ ▒░   ▒ ▒  ▒ ░   ░▓   ░▒   ▒ 
                              ░ ░░  ░░   ░▒ ░     ░  ▒     ░ ▒ ▒░ ░ ░░   ░ ▒░ ░      ▒ ░  ░   ░ 
                                ░░   ░    ░     ░        ░ ░ ░ ▒     ░   ░ ░  ░ ░    ▒ ░░ ░   ░ 
                                 ░   ░    ░     ░ ░          ░ ░           ░         ░        ░ 
                                ░               ░                                                                                                
                                                Only Education   
                                            By ??? | discord.gg/???
                                                API: Connected 
""",1))

print(f"Loading your config file...")
time.sleep(3)
print(f"Finished loading your config file!")
time.sleep(0.5)
print("")
print(f"Your data:")
print("")
print(f"BTC:{wallet_link_btc}")
print("")
print(f"ETH:{wallet_link_eth}")
print("")
print(f"LIC: {license_key}")
time.sleep(3)
os.system("cls")

print(Colorate.Horizontal(Colors.purple_to_blue, """
                               ██▒   █▓▒██   ██▒    ███▄ ▄███▓ ██▓ ███▄    █ ▓█████  ██▀███  
                            ▓██░   █▒▒▒ █ █ ▒░   ▓██▒▀█▀ ██▒▓██▒ ██ ▀█   █ ▓█   ▀ ▓██ ▒ ██▒
                             ▓██  █▒░░░  █   ░   ▓██    ▓██░▒██▒▓██  ▀█ ██▒▒███   ▓██ ░▄█ ▒
                              ▒██ █░░ ░ █ █ ▒    ▒██    ▒██ ░██░▓██▒  ▐▌██▒▒▓█  ▄ ▒██▀▀█▄  
                               ▒▀█░  ▒██▒ ▒██▒   ▒██▒   ░██▒░██░▒██░   ▓██░░▒████▒░██▓ ▒██▒
                               ░ ▐░  ▒▒ ░ ░▓ ░   ░ ▒░   ░  ░░▓  ░ ▒░   ▒ ▒ ░░ ▒░ ░░ ▒▓ ░▒▓░
                               ░ ░░  ░░   ░▒ ░   ░  ░      ░ ▒ ░░ ░░   ░ ▒░ ░ ░  ░  ░▒ ░ ▒░
                                 ░░   ░    ░     ░      ░    ▒ ░   ░   ░ ░    ░     ░░   ░ 
                                  ░   ░    ░            ░    ░           ░    ░  ░   ░     
                                 ░                                                         
                                                Only Education   
                                            By ??? | discord.gg/???
                                                API: Connected 

                                                     Vx.py
                                          Do you want to use proxies?
                                            1. Yes     or     2. No
""",1))

def file_len():
    with open("proxies.txt") as f:
        for i, _ in enumerate(f):
            pass
    return i

option = int(input("Choose your option: "))

while option !=0:
  if option == 1:
    print(Fore.GREEN + "Imported " + str(file_len()) + " Proxies")
    os.system("cls")
    time.sleep(999999999999999)
  elif option == 2:
    print(Fore.RED + "Not using Proxies")
    os.system("cls")
    time.sleep(999999999999999)


print(Colorate.Horizontal(Colors.purple_to_blue, """
                               ██▒   █▓▒██   ██▒    ███▄ ▄███▓ ██▓ ███▄    █ ▓█████  ██▀███  
                            ▓██░   █▒▒▒ █ █ ▒░   ▓██▒▀█▀ ██▒▓██▒ ██ ▀█   █ ▓█   ▀ ▓██ ▒ ██▒
                             ▓██  █▒░░░  █   ░   ▓██    ▓██░▒██▒▓██  ▀█ ██▒▒███   ▓██ ░▄█ ▒
                              ▒██ █░░ ░ █ █ ▒    ▒██    ▒██ ░██░▓██▒  ▐▌██▒▒▓█  ▄ ▒██▀▀█▄  
                               ▒▀█░  ▒██▒ ▒██▒   ▒██▒   ░██▒░██░▒██░   ▓██░░▒████▒░██▓ ▒██▒
                               ░ ▐░  ▒▒ ░ ░▓ ░   ░ ▒░   ░  ░░▓  ░ ▒░   ▒ ▒ ░░ ▒░ ░░ ▒▓ ░▒▓░
                               ░ ░░  ░░   ░▒ ░   ░  ░      ░ ▒ ░░ ░░   ░ ▒░ ░ ░  ░  ░▒ ░ ▒░
                                 ░░   ░    ░     ░      ░    ▒ ░   ░   ░ ░    ░     ░░   ░ 
                                  ░   ░    ░            ░    ░           ░    ░  ░   ░     
                                 ░                                                         
                                                Only Education   
                                            By ??? | discord.gg/???
                                                API: Connected 

                                                     Vx.py
                                                Starting minning...
""",1))

time.sleep(3)

# DONT DELETE THIS OR CODE WILL WONT WORK !
# DONT DELETE THIS OR CODE WILL WONT WORK !
# DONT DELETE THIS OR CODE WILL WONT WORK !
# DONT DELETE THIS OR CODE WILL WONT WORK !

def id_gen(size=40, chars=string.ascii_uppercase + string.digits):
    return "".join(random.choice(chars) for _ in range(size))

tries = 0

while(True):
    if(tries > random.randint(100000000, 2500000000)): # chance to get fake btc
        print(Fore.CYAN +"[-]"+ Fore.RED + " bc1" + id_gen() + Fore.GREEN +" |  Valid  |  " + str(round(random.uniform(0,2), 4)), "BTC")
        print(Fore.GREEN +"Withdrawing to your Wallet...")
        time.sleep(10)
        tries = 0
        print(Fore.GREEN + "Done!")
        time.sleep(1)
    else:
        print(Fore.CYAN +"[-]"+ Fore.RED + " bc1" + id_gen() + Fore.CYAN +" | InValid |  " + "0.0000 BTC")
        tries += 1
