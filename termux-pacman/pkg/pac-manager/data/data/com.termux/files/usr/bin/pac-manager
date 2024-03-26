#!/usr/bin/env python3

import os 

banner = """

 ________  ________  ___  __       
|\   __  \|\   __  \|\  \|\  \     
\ \  \|\  \ \  \|\  \ \  \/  /|_   
 \ \   ____\ \   __  \ \   ___  \  
  \ \  \___|\ \  \ \  \ \  \\ \  \ 
   \ \__\    \ \__\ \__\ \__\\ \__\
    \|__|     \|__|\|__|\|__| \|__|
                                   
                                   
                                   

"""

prompt = "select >> "

prompt2 = "package >> "

prompt3 = "(install/search) >> "

def start():
    while True:
        os.system("clear")
        print(banner)
        print("Which Distro do you use?")
        print("[1] Debian (Ubuntu/Kali)")
        print("[2] Arch Linux")
        print("[3] Alpine")
        print("[4] Termux")
        print("[0] Exit")
        
        choice = input(prompt).lower()
        
        if choice == '0':
            os.system("clear")
            break
        elif choice == '1':
            debian()
        elif choice == '2':
            arch()
        elif choice == '3':
            alpine()
        elif choice == '4':
            termux()
        else:
            print("Invalid Option")
            
def debian():
    while True:
        os.system("clear")
        print(banner)
        print("Are you in Root Mode")
        print("[1] Yes, I'm in Root Mode")
        print("[2] No, I'm not in Root Mode")
        print("[0] Exit")
        
        choice = input(prompt).lower()
        
        if choice == '0':
            break
        elif choice == '1':
            debian_root()
        elif choice == '2':
            debian_noroot()
        else:
            print("Invalid Option")
        
def debian_root():
    os.system("clear")
    print(banner)
    print("What do you want?")
    
    choice = input(prompt3).lower()
    
    if choice == 'install':
        package = input(prompt2)
        cmd = f"apt install {package}"
        os.system(cmd)
    elif choice == 'i':
        package = input(prompt2)
        cmd = f"apt install {package}"
        os.system(cmd)
    elif choice == 'search':
        package = input(prompt2)
        cmd = f"apt search {package}"
        os.system(cmd)
    elif choice == 's':
        package = input(prompt2)
        cmd = f"apt search {package}"
        os.system(cmd)
    else:
        print("Invalid Option")
        
def debian_noroot():
    os.system("clear")
    print(banner)
    print("What do you want?")
    
    choice = input(prompt3).lower()
    
    if choice == 'install':
        package = input(prompt2)
        cmd = f"sudo apt install {package}"
        os.system(cmd)
    elif choice == 'i':
        package = input(prompt2)
        cmd = f"sudo apt install {package}"
        os.system(cmd)
    elif choice == 'search':
        package = input(prompt2)
        cmd = f"sudo apt search {package}"
        os.system(cmd)
    elif choice == 's':
        package = input(prompt2)
        cmd = f"sudo apt search {package}"
        os.system(cmd)
    else:
        print("Invalid Option")
        
def arch():
    while True:
        os.system("clear")
        print(banner)
        print("Are you in Root Mode")
        print("[1] Yes, I'm in Root Mode")
        print("[2] No, I'm not in Root Mode")
        print("[0] Exit")
        
        choice = input(prompt).lower()
        
        if choice == '0':
            break
        elif choice == '1':
            arch_root()
        elif choice == '2':
            arch_noroot()
        else:
            print("Invalid Option")
        
def arch_root():
    os.system("clear")
    print(banner)
    print("What do you want?")
    
    choice = input(prompt3).lower()
    
    if choice == 'install':
        package = input(prompt2)
        cmd = f"pacman -S {package}"
        os.system(cmd)
    elif choice == 'i':
        package = input(prompt2)
        cmd = f"pacman -S {package}"
        os.system(cmd)
    elif choice == 'search':
        package = input(prompt2)
        cmd = f"pacman -S {package}"
        os.system(cmd)
    elif choice == 's':
        package = input(prompt2)
        cmd = f"pacman -S {package}"
        os.system(cmd)
    else:
        print("Invalid Option")
        
def arch_noroot():
    os.system("clear")
    print(banner)
    print("What do you want?")
    
    choice = input(prompt3).lower()
    
    if choice == 'install':
        package = input(prompt2)
        cmd = f"sudo pacman -S {package}"
        os.system(cmd)
    elif choice == 'i':
        package = input(prompt2)
        cmd = f"sudo pacman -S {package}"
        os.system(cmd)
    elif choice == 'search':
        package = input(prompt2)
        cmd = f"sudo pacman -S {package}"
        os.system(cmd)
    elif choice == 's':
        package = input(prompt2)
        cmd = f"sudo pacman -S {package}"
        os.system(cmd)
    else:
        print("Invalid Option")
        
def alpine():
    while True:
        os.system("clear")
        print(banner)
        print("Are you in Root Mode")
        print("[1] Yes, I'm in Root Mode")
        print("[2] No, I'm not in Root Mode")
        print("[0] Exit")
        
        choice = input(prompt).lower()
        
        if choice == '0':
            break
        elif choice == '1':
            alpine_root()
        elif choice == '2':
            alpine_noroot()
        else:
            print("Invalid Option")
        
def alpine_root():
    os.system("clear")
    print(banner)
    print("What do you want?")
    
    choice = input(prompt3).lower()
    
    if choice == 'install':
        package = input(prompt2)
        cmd = f"apk add {package}"
        os.system(cmd)
    elif choice == 'i':
        package = input(prompt2)
        cmd = f"apk add {package}"
        os.system(cmd)
    elif choice == 'search':
        package = input(prompt2)
        cmd = f"apk add {package}"
        os.system(cmd)
    elif choice == 's':
        package = input(prompt2)
        cmd = f"apk add {package}"
        os.system(cmd)
    else:
        print("Invalid Option")
        
def alpine_noroot():
    os.system("clear")
    print(banner)
    print("What do you want?")
    
    choice = input(prompt3).lower()
    
    if choice == 'install':
        package = input(prompt2)
        cmd = f"sudo apk add {package}"
        os.system(cmd)
    elif choice == 'i':
        package = input(prompt2)
        cmd = f"sudo apk add {package}"
        os.system(cmd)
    elif choice == 'search':
        package = input(prompt2)
        cmd = f"sudo apk add {package}"
        os.system(cmd)
    elif choice == 's':
        package = input(prompt2)
        cmd = f"sudo apk add {package}"
        os.system(cmd)
    else:
        print("Invalid Option")
        
def termux():
    while True:
        os.system("clear")
        print(banner)
        print("Which Manager?")
        print("[1] Apt")
        print("[2] Pacman")
        print("[3] I'm not sure")
        print("[0] Exit")
        
        choice = input(prompt).lower()
        
        if choice == '0':
            break
        if choice == '1':
            termux_apt()
        if choice == '2':
            termux_pacman()
        if choice == '3':
            termux_pkg()
        else:
            print("Invalid Option")
            
def termux_apt():
    os.system("clear")
    print(banner)
    print("What do you want?")
    
    choice = input(prompt3).lower()
    
    if choice == 'install':
        package = input(prompt2)
        cmd = f"apt install {package}"
        os.system(cmd)
    elif choice == 'i':
        package = input(prompt2)
        cmd = f"apt install {package}"
        os.system(cmd)
    elif choice == 'search':
        package = input(prompt2)
        cmd = f"apt search {package}"
        os.system(cmd)
    elif choice == 's':
        package = input(prompt2)
        cmd = f"apt search {package}"
        os.system(cmd)
    else:
        print("Invalid Option")
        
def termux_pacman():
    os.system("clear")
    print(banner)
    print("What do you want?")
    
    choice = input(prompt3).lower()
    
    if choice == 'install':
        package = input(prompt2)
        cmd = f"pacman -S {package}"
        os.system(cmd)
    elif choice == 'i':
        package = input(prompt2)
        cmd = f"pacman -S {package}"
        os.system(cmd)
    elif choice == 'search':
        package = input(prompt2)
        cmd = f"pacman -S {package}"
        os.system(cmd)
    elif choice == 's':
        package = input(prompt2)
        cmd = f"pacman -S {package}"
        os.system(cmd)
    else:
        print("Invalid Option")
        
def termux_pkg():
    os.system("clear")
    print(banner)
    print("What do you want?")
    
    choice = input(prompt3).lower()
    
    if choice == 'install':
        package = input(prompt2)
        cmd = f"pkg install {package}"
        os.system(cmd)
    elif choice == 'i':
        package = input(prompt2)
        cmd = f"pkg install {package}"
        os.system(cmd)
    elif choice == 'search':
        package = input(prompt2)
        cmd = f"pkg search {package}"
        os.system(cmd)
    elif choice == 's':
        package = input(prompt2)
        cmd = f"pkg search {package}"
        os.system(cmd)
    else:
        print("Invalid Option")
        
start()