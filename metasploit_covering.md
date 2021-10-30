## Selecting a Target
TARGET environment variable

## Generating a Payload:
Metasploit 3.0

## Usage Open
msf > msfcli -h

## Connect to the host, specify the IP
msf > connect [IPADDRESS]

## Exit and Quit
msf > exit

## Display information for selected exploit
msf > exploit(windows) > info

### Select a payload
msf > use windows/shell_reverse_tcp
msf payload(shell_reverse_tcp) > generate -h

## Usage options:
OPTIONS:
 -b <opt> | The list of characters to avoid '\x00\xff'
 -e <opt> | The name of the encoder module to use
 -h       | Help banner
 -o <opt> | A comma separated list of options in VAR=VAL format
 -s <opt> | NOP sled length
 -t <opt> | The output type: ruby, perl,c, or raw
  
 msf > payload(shell_reverse_tcp) >
  
## To comeback from the current exploit or module
  msf > exploit(msf main window) > back
