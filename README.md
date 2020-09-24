**Мой IP-адрес:192.168.0.20**

![Мой IP-адрес:192.168.0.20](https://raw.githubusercontent.com/kop4anskiy/pr2/master/1.png)

**В заголовке содержится 20 байт, общая длина 60 байт**

**TTL=108**

![](https://raw.githubusercontent.com/kop4anskiy/pr2/master/2.png)

**Запускаем cmd**

![](https://raw.githubusercontent.com/kop4anskiy/pr2/master/4.png)

**SRC-Port=59162**
**dst-port=53**

![](https://raw.githubusercontent.com/kop4anskiy/pr2/master/5.png)

![](https://raw.githubusercontent.com/kop4anskiy/pr2/master/6.png)

![](https://raw.githubusercontent.com/kop4anskiy/pr2/master/7.png)

**ICMP-протокол**

![](https://raw.githubusercontent.com/kop4anskiy/pr2/master/8.png)

**Frame=211;74 bytes(592 bytes)**

**IPV4;Src: 192.168.0.24, Dst: 8.8.8.8**

![](https://raw.githubusercontent.com/kop4anskiy/pr2/master/9.png)

**Lenght=42 bytes
sender MAC-адрес micro-st_ec:7d:26
sender ip 192.168.0.20
target ip 192.168.0.17**

![](https://raw.githubusercontent.com/kop4anskiy/pr2/master/10.png)


![](https://raw.githubusercontent.com/kop4anskiy/pr2/master/11.png)

**IP-SRC**-*пакет, содержащий в себе IP-адрес рабочей станции, от которой он поступил*
**IP-адрес 178.248.235.236 , TTL=57, IPv4, ICMP-protocol** 

![](https://raw.githubusercontent.com/kop4anskiy/pr2/master/ip_src.jpg)

**IP-DST**-*пакет, содержащий в себе IP-адрес рабочей станции, которой он адресован.*
**IP-адрес 178.248.235.236 , TTL=57, IPv4, ICMP-protocol** 

![](https://raw.githubusercontent.com/kop4anskiy/pr2/master/ip_dst.jpg)

**ip.addr**-*Фильтрует трафик по определенному IP-адресу*

IPишник 2.20.74.161, ping=44ms, dst-port=80, TCP-protocol, IPv4

![](https://raw.githubusercontent.com/kop4anskiy/pr2/master/addr.png)

**udp.srcport**-*UDP порт отправителя*

***UDP(17)-protocol , dst-port=57433***

![](https://raw.githubusercontent.com/kop4anskiy/pr2/master/udp.src.jpg)

**arp.src.hw_mac** - *Протокол ARP – MAC адрес отправителя*

**eth.src**-*MAC-адрес отправителя*

**MAC-adress=30:9c:23:ec:7d:26, src-port:52409**

![](https://raw.githubusercontent.com/kop4anskiy/pr2/master/eth.src.jpg)

**eth.dst**-*MAC-адрес получателя*

**MAC-adress=d4:vf:7f:7g:67:ao , IPv4, dst.port=443 , TotalLenght=40, HeaderLenght=20 bytes

![](https://raw.githubusercontent.com/kop4anskiy/pr2/master/eth.dst.jpg)

**КОНЕЦ 2 ПРАКТИЧЕСКОЙ РАБОТЫ, МНЕ ПОНРАВИЛОСЬ РАБОТАТЬ С WireShark'ом, интересная вещь**

![](https://raw.githubusercontent.com/kop4anskiy/pr2/master/1402575952_1028282835.gif)
