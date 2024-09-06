```
python3 -c 'import pty;pty.spawn("/bin/bash")’    
export TERM=xterm  # This will give you commands as clear
ctrl + z # To background the session 
stty raw -echo; fg  # You get an interactive lovely shell!
```
