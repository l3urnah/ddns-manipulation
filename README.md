# ddns-manipulation
create all the things for hosts

read IP from DCHP or create a reservation for the new host 
create monitoring via api
create dns entry 

nsupdate
 server localhost
 update add blubb12.nyc3.example.com. 3600 A 192.168.50.112
 send
 update add 112.50.168.192.in-addr.arpa 3600 PTR blubb12.nyc3.example.com.
 send
 quit
