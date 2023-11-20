# Week 2: Study IoT and Terminal

## Internet of Things Lesson 1

The provided [lesson](https://github.com/kevinwlu/iot/tree/master/lesson1) covers a variety of interconnected technology topics. It emphasizes that innovation often happens step by step and sometimes with a bit of luck, rather than relying solely on extraordinary genius. At the core of these technological advancements is the Internet of Things (IoT), which has a complex structure based on the [OSI model](https://en.wikipedia.org/wiki/OSI_model) and uses protocols like [TCP](https://en.wikipedia.org/wiki/Transmission_Control_Protocol), [UDP](https://en.wikipedia.org/wiki/User_Datagram_Protocol), and [IP](https://en.wikipedia.org/wiki/Internet_Protocol) for smooth data exchange. IoT heavily relies on wireless technologies such as Wi-Fi, Bluetooth, Zigbee, and RFID. The development of wireless communication is closely linked to the evolution of 5G networks, which introduce concepts like enhanced mobile broadband (eMBB), ultra-reliable and low-latency communications (URLLC), and massive machine-type communications (mMTC), paving the way for [6G technology](https://en.wikipedia.org/wiki/6G_(network)). Edge and cloud computing are essential in IoT, with cloud services like [AWS](https://en.wikipedia.org/wiki/Amazon_Web_Services), [Azure](https://en.wikipedia.org/wiki/Microsoft_Azure), and [Google Cloud](https://en.wikipedia.org/wiki/Google_Cloud_Platform) providing critical support. In addition, software-defined networking and radio are changing how networks operate, and automation protocols and DevOps practices are making software development more efficient. These technologies are practically applied in setting up Raspberry Pi devices, with [SSH](https://en.wikipedia.org/wiki/Secure_Shell) and [VNC](https://en.wikipedia.org/wiki/Virtual_Network_Computing) allowing remote access. The text also discusses IoT complexity levels, security measures like zero trust, and alternative methods for remote access, highlighting their importance in the broader technology landscape. Moreover, it covers hardware components like Raspberry Pi, operating systems such as Raspberry Pi OS, and authentication methods like [RSA](https://en.wikipedia.org/wiki/RSA_(cryptosystem)) and [DSA](https://en.wikipedia.org/wiki/Digital_Signature_Algorithm), all contributing to the intricate world of technology and innovation.

## Internet of Things Lesson 2

Raspberry Pi has the tradition of naming computer companies after fruits and the original plan to make it primarily for Python programming. Beyond the name, the [lesson](https://github.com/kevinwlu/iot/tree/master/lesson2) explores microprocessors, ARM architecture, and assembly language, gaining insights into the core of computing. Understanding terms like [GPIO](https://en.wikipedia.org/wiki/General-purpose_input/output) and [I2C](https://en.wikipedia.org/wiki/I%C2%B2C) helps underscore the versatility of Raspberry Pi, showcasing its ability to interface with various devices. Moreover, USB peripherals like webcams and microphones can be used with the Raspberry Pi for real-world applications.

## Terminal Assignment

List of commands ran in the terminal

### Commands

netstat

```
Active Internet connections
Proto Recv-Q Send-Q  Local Address          Foreign Address        (state)    
Redacted IP addresses and ports
Redacted IP addresses and ports
Redacted IP addresses and ports
Redacted IP addresses and ports
Redacted IP addresses and ports
Redacted IP addresses and ports
Redacted IP addresses and ports
Redacted IP addresses and ports
Redacted IP addresses and ports
Redacted IP addresses and ports
Redacted IP addresses and ports
Redacted IP addresses and ports
Redacted IP addresses and ports
Redacted IP addresses and ports
```

ping localhost

```
PING localhost (Redacted): 56 data bytes
64 bytes from Redacted: icmp_seq=0 ttl=64 time=0.117 ms
64 bytes from Redacted: icmp_seq=1 ttl=64 time=0.222 ms
64 bytes from Redacted: icmp_seq=2 ttl=64 time=0.179 ms
64 bytes from Redacted: icmp_seq=3 ttl=64 time=0.189 ms
64 bytes from Redacted: icmp_seq=4 ttl=64 time=0.228 ms
64 bytes from Redacted: icmp_seq=5 ttl=64 time=0.253 ms
64 bytes from Redacted: icmp_seq=6 ttl=64 time=0.215 ms
64 bytes from Redacted: icmp_seq=7 ttl=64 time=0.202 ms
64 bytes from Redacted: icmp_seq=8 ttl=64 time=0.151 ms
64 bytes from Redacted: icmp_seq=9 ttl=64 time=0.226 ms
64 bytes from Redacted: icmp_seq=10 ttl=64 time=0.099 ms
64 bytes from Redacted: icmp_seq=11 ttl=64 time=0.132 ms
^C
--- localhost ping statistics ---
12 packets transmitted, 12 packets received, 0.0% packet loss
round-trip min/avg/max/stddev = 0.099/0.184/0.253/0.047 ms
```

ifconfig

```
lo0: flags=8049<UP,LOOPBACK,RUNNING,MULTICAST> mtu 16384
	options=1203<RXCSUM,TXCSUM,TXSTATUS,SW_TIMESTAMP>
	inet Redacted netmask 0xff000000 
	inet6 ::1 prefixlen 128 
	inet6 Redacted prefixlen 64 scopeid 0x1 
	nd6 options=201<PERFORMNUD,DAD>
gif0: flags=8010<POINTOPOINT,MULTICAST> mtu 1280
stf0: flags=0<> mtu 1280
anpi0: flags=8863<UP,BROADCAST,SMART,RUNNING,SIMPLEX,MULTICAST> mtu 1500
	options=400<CHANNEL_IO>
	ether Redacted
	inet6 Redacted prefixlen 64 scopeid 0x4 
	nd6 options=201<PERFORMNUD,DAD>
	media: none
	status: inactive
anpi1: flags=8863<UP,BROADCAST,SMART,RUNNING,SIMPLEX,MULTICAST> mtu 1500
	options=400<CHANNEL_IO>
	ether Redacted
	inet6 Redacted prefixlen 64 scopeid 0x5 
	nd6 options=201<PERFORMNUD,DAD>
	media: none
	status: inactive
anpi2: flags=8863<UP,BROADCAST,SMART,RUNNING,SIMPLEX,MULTICAST> mtu 1500
	options=400<CHANNEL_IO>
	ether Redacted
	inet6 Redacted prefixlen 64 scopeid 0x6 
	nd6 options=201<PERFORMNUD,DAD>
	media: none
	status: inactive
en4: flags=8863<UP,BROADCAST,SMART,RUNNING,SIMPLEX,MULTICAST> mtu 1500
	options=400<CHANNEL_IO>
	ether Redacted
	nd6 options=201<PERFORMNUD,DAD>
	media: none
	status: inactive
en5: flags=8863<UP,BROADCAST,SMART,RUNNING,SIMPLEX,MULTICAST> mtu 1500
	options=400<CHANNEL_IO>
	ether Redacted
	nd6 options=201<PERFORMNUD,DAD>
	media: none
	status: inactive
en6: flags=8863<UP,BROADCAST,SMART,RUNNING,SIMPLEX,MULTICAST> mtu 1500
	options=400<CHANNEL_IO>
	ether Redacted
	nd6 options=201<PERFORMNUD,DAD>
	media: none
	status: inactive
en1: flags=8963<UP,BROADCAST,SMART,RUNNING,PROMISC,SIMPLEX,MULTICAST> mtu 1500
	options=460<TSO4,TSO6,CHANNEL_IO>
	ether Redacted
	media: autoselect <full-duplex>
	status: inactive
en2: flags=8963<UP,BROADCAST,SMART,RUNNING,PROMISC,SIMPLEX,MULTICAST> mtu 1500
	options=460<TSO4,TSO6,CHANNEL_IO>
	ether Redacted
	media: autoselect <full-duplex>
	status: inactive
en3: flags=8963<UP,BROADCAST,SMART,RUNNING,PROMISC,SIMPLEX,MULTICAST> mtu 1500
	options=460<TSO4,TSO6,CHANNEL_IO>
	ether Redacted
	media: autoselect <full-duplex>
	status: inactive
ap1: flags=8802<BROADCAST,SIMPLEX,MULTICAST> mtu 1500
	options=400<CHANNEL_IO>
	ether Redacted
	media: autoselect
en0: flags=8863<UP,BROADCAST,SMART,RUNNING,SIMPLEX,MULTICAST> mtu 1500
	options=6463<RXCSUM,TXCSUM,TSO4,TSO6,CHANNEL_IO,PARTIAL_CSUM,ZEROINVERT_CSUM>
	ether Redacted
	inet6 Redacted prefixlen 64 secured scopeid 0xf 
	inet Redacted netmask 0xffffe000 broadcast Redacted
	nd6 options=201<PERFORMNUD,DAD>
	media: autoselect
	status: active
bridge0: flags=8863<UP,BROADCAST,SMART,RUNNING,SIMPLEX,MULTICAST> mtu 1500
	options=63<RXCSUM,TXCSUM,TSO4,TSO6>
	ether Redacted
	Configuration:
		id 0:0:0:0:0:0 priority 0 hellotime 0 fwddelay 0
		maxage 0 holdcnt 0 proto stp maxaddr 100 timeout 1200
		root id 0:0:0:0:0:0 priority 0 ifcost 0 port 0
		ipfilter disabled flags 0x0
	member: en1 flags=3<LEARNING,DISCOVER>
	        ifmaxaddr 0 port 10 priority 0 path cost 0
	member: en2 flags=3<LEARNING,DISCOVER>
	        ifmaxaddr 0 port 11 priority 0 path cost 0
	member: en3 flags=3<LEARNING,DISCOVER>
	        ifmaxaddr 0 port 12 priority 0 path cost 0
	nd6 options=201<PERFORMNUD,DAD>
	media: <unknown type>
	status: inactive
awdl0: flags=8843<UP,BROADCAST,RUNNING,SIMPLEX,MULTICAST> mtu 1500
	options=6463<RXCSUM,TXCSUM,TSO4,TSO6,CHANNEL_IO,PARTIAL_CSUM,ZEROINVERT_CSUM>
	ether Redacted
	inet6 Redacted prefixlen 64 scopeid 0x11 
	nd6 options=201<PERFORMNUD,DAD>
	media: autoselect
	status: active
llw0: flags=8863<UP,BROADCAST,SMART,RUNNING,SIMPLEX,MULTICAST> mtu 1500
	options=400<CHANNEL_IO>
	ether Redacted
	inet6 Redacted prefixlen 64 scopeid 0x12 
	nd6 options=201<PERFORMNUD,DAD>
	media: autoselect
	status: inactive
utun0: flags=8051<UP,POINTOPOINT,RUNNING,MULTICAST> mtu 1380
	inet6 Redacted prefixlen 64 scopeid 0x13 
	nd6 options=201<PERFORMNUD,DAD>
utun1: flags=8051<UP,POINTOPOINT,RUNNING,MULTICAST> mtu 2000
	inet6 Redacted prefixlen 64 scopeid 0x14 
	nd6 options=201<PERFORMNUD,DAD>
utun2: flags=8051<UP,POINTOPOINT,RUNNING,MULTICAST> mtu 1000
	inet6 Redacted prefixlen 64 scopeid 0x15 
	nd6 options=201<PERFORMNUD,DAD>
utun3: flags=8051<UP,POINTOPOINT,RUNNING,MULTICAST> mtu 1380
	inet6 Redacted prefixlen 64 scopeid 0x16 
	nd6 options=201<PERFORMNUD,DAD>
utun4: flags=8051<UP,POINTOPOINT,RUNNING,MULTICAST> mtu 1380
	inet6 Redacted prefixlen 64 scopeid 0x17 
	nd6 options=201<PERFORMNUD,DAD>
```

 df

 ```
 Filesystem     512-blocks      Used Available Capacity iused      ifree %iused  Mounted on
/dev/disk3s1s1  965595304  23413280 355322688     7%  356093 1776613440    0%   /
devfs                 405       405         0   100%     702          0  100%   /dev
/dev/disk3s6    965595304  14680208 355322688     4%       7 1776613440    0%   /System/Volumes/VM
/dev/disk3s2    965595304  19212152 355322688     6%    1172 1776613440    0%   /System/Volumes/Preboot
/dev/disk3s4    965595304   1233104 355322688     1%     283 1776613440    0%   /System/Volumes/Update
/dev/disk1s2      1024000     12328    984968     2%       1    4924840    0%   /System/Volumes/xarts
/dev/disk1s1      1024000     12664    984968     2%      31    4924840    0%   /System/Volumes/iSCPreboot
/dev/disk1s3      1024000      4320    984968     1%      52    4924840    0%   /System/Volumes/Hardware
/dev/disk3s5    965595304 548303792 355322688    61% 5330210 1776613440    0%   /System/Volumes/Data
map auto_home           0         0         0   100%       0          0  100%   /System/Volumes/Data/home
/dev/disk5s1      8069120   7585864    451256    95%  273178    2256280   11%   /Library/Developer/CoreSimulator/Volumes/watchOS_20S75
/dev/disk3s1    965595304  23413280 355322688     7%  356052 1776613440
```




