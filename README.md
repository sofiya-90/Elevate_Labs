# *Elevate_Labs*
1.Run ipconfig command to get the ip address of windows machine.

2. Run ping <target IP> to check the connection.
   
3.Run nmap command along with the options to find the open ports in the ip < nmap -sS -p- target IP >. -sS to perform the TCP syn scan. -p- to perform the port scan.

4.Result-
Starting Nmap 7.94SVN ( https://nmap.org ) at 2025-06-24 03:53 EDT
Nmap scan report for 192.168.208.2
135/tcp  open  msrpc
139/tcp  open  netbios-ssn
445/tcp  open  microsoft-ds
5357/tcp open  wsdapi
6646/tcp open  unknown
Above mentioned ports were found open .

![Image](https://github.com/user-attachments/assets/12742faa-d33e-457b-9968-09e9d1a5f990)
