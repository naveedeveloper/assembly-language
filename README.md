# Assembly-Language-Codes

# Install Doxbox  
    sudo apt install dosbox 
    doxbox 

    # Inside dosbox (give it some path in your host machine) 
    # Put extracted contents of the zip file and .asm files in this folder on your host machine 
    
    mount c /home/nam/ee213 

    c: 

    # Assemble and run 
    nasm c.asm -o c.com 
    afd c.com 
