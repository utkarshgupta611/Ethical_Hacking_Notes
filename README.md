# Ethical_Hacking_Notes
#                                          ETHICAL HACKING
## ------------------------------------------------------------------------------------------------------

## TYpe of Attack on a system
=========*******=============
* Operating System Attack.
* Misconfigration Attack.
* Application Level Attack.
* Shrink - Wrap Code Attack.

## Networking , type Of networking , IP address, port
================**************=========================

## What is computer Networking?
-----------------------------

1)communication - 
2)share of software , info, file
3)Security - tcp.ip etc
4)sharing of hardware
5)sharing of data

## ISP - > Internet service Provider -(Network Provider)
------

isp -->(router/broadband)  --> Device(mobile , lap, system)
isp provide ip to router one public and one private(192.168.0.1 --default)
source ip ---> desitination ip

## Type Of Networking ?
-------------------------

*LAN(Local Area Network)
==> all device connected to a router to a local are
*MAN(Metropolitian Area Network) ==> network provide to a company , house larger than lan
*WAN(Wide Area Network) ==>provide area to major area like state , country.

## What is IP Address?
---------------------

IP = Internet protocol Address.

eg = 17.172.224.47 has total 4 part each of 
- 1byte/8bits total of 32bits/4byte.
- 1st pair tell us country, 2nd pair tell us state, 3rd pair tell us isp, 4th pair tell us device.

 ## IPv4 VS IPv6
--------------------

* Ipv4 - address size :32 bit, dotted decimal notation, 192.149.0.0/24, 4.7 billion ip can me made at atime and 
         short for now a days
* IPv6 - address size :128 bit, 3ffe:f200:0234:ab00:0123:4567:8901:bcd , 340 trillion trillion trillion ip can be made

## Type Of IP Address
---------------------

- Public- router this only know even using hgotspot host ip has shared to sites.
- Private - under lan/router
- Static - it is fix ip, on hosting
- Dynamic - change dynamically, while discounting.


## Role Of Port In Networking
=========*******=============

total port = 65536
states open closed filtered
well known port = 0 to 1023
registered port = 1024 to 49151
Dynamic = 49152 to 65545

## Default Ports
----------------

port Number      Protocol          Application
20		                TCP               FTP Data
21		                TCP		           FTP control
22		                TCP		              SSH
25 		               TCP                SMTP
53		              TCP, UDP             DNS
80		               TCP                HTTP(wwW)
110		              TCP                POP3
443		              TCP                SSL

## OSI VS TCP
==*******=====

* OSI MOdel=>open System Interconnecttion Model.
----------------------------------------------------

it provide 7 layer between two system to provide connection. it always read bottom to up.
&layer(Application, Presentation, Session, transport, Network, data Layer, Physical)

* TCP/IP model => Transmision Control Protocol/Internet Ptotocol.
-------------------------------------------------------------------

it is practicall version of osi model working on wan using 4 to 5 layer.
 
 - 4layer(Application layer, transpirtation layer, Internet layer, Network access layer)
 - 5layer(Application layer, transpirtation layer, Internet layer, Data-link layer, physival layer)


## Networking Protocoal and thier Working
========================================

## what is Networking Protocoal?
------------------------------

Set of rule , how data is transmted , Decice Communication

## How TCP work?
---------------

tcp has 6 flag 
* URG(Urgent) - Data Contained the packet should be processed immediately.
* FIN(Finish) - there will be no further transmission.
* RST(Rest) - Resests a connection.
* PSH(Push) - Send all buffered data immediately.
* ACK(Acknowlegment) - Acknowlegment the recipt of a packet.
* SYN(Sychronize) - intitate connection between hosts.
 ==> TCP THREE _ WAY HANDSHAKE
 ==> TCP Session Termination.
