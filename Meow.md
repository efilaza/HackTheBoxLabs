Step 1 : Connect to PwnBox 
Step 2: Spawn the trarget Machine to acquire its IP Address
Target IP: 10.129.25.177

Step 3: Ping the target Machine![9e69697b4523ce44ca4002855deeefab.png](../_resources/9e69697b4523ce44ca4002855deeefab.png)

Step 4: nmap -sV 10.129.25.177
![1ced87f2243928b8e47b44d8611f5939.png](../_resources/1ced87f2243928b8e47b44d8611f5939.png)

Open telnet port 23/tcp telnet

Step 5 : telnet 10.129.25.177
![8487c7084f15c2f5224029d14cd249a3.png](../_resources/8487c7084f15c2f5224029d14cd249a3.png)

Trying usual usernames with no password:
admin
administrator
root
![f2592d0f619aecf88d0d793d36a0bf73.png](../_resources/f2592d0f619aecf88d0d793d36a0bf73.png)

Username  "root" does the job! ![5e9d0ec13d657d0845fe04be6c7a2930.png](../_resources/5e9d0ec13d657d0845fe04be6c7a2930.png)

Step 6 : ls
![6971c98522db12c7c92314e397b99162.png](../_resources/6971c98522db12c7c92314e397b99162.png)

Step 7: cat flag.txt
![3633849740ce5f3a7f9f2dc8a4e84345.png](../_resources/3633849740ce5f3a7f9f2dc8a4e84345.png)
