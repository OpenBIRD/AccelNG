# AccelNG

##About

AccelNG stands for Accelerator Next Generation. 

AccelNG is a DNS recursive server built base on [dnspod-sr](https://github.com/DNSPod/dnspod-sr) and [FasterApple's DNS database](https://github.com/FasterApple/fasterapple)

The goal of the project is to provide a faster and safer DNS service in China. We are trying to eliminate DNS corruption and provide the users the best Internet experience.

##Performance

###Testing Environment:

Gigabyte NIC, 4 core CPU, 4G RAM and 64-bits Linux

###Result:

- dnspod-sr: 150k qps
- BIND 9.9: 70k qps
- unbound 4.7: 80k qps

*Data from [dnspod/dnspod-sr](https://github.com/DNSPod/dnspod-sr#%E6%80%A7%E8%83%BD)

#Installations

Download the source code：
```
    git clone https://github.com/FasterApple/AccelNG.git
    cd dnspod-sr
```

Or：
```
    https://github.com/FasterApple/AccelNG/archive/master.zip
```

Compile the source code：
```
    cd src
    make
```

Run
```
    ./dnspod-sr
```

For more details, please see [INSTALL.md](./INSTALL.md).

#License

[dnspod/dnspod-sr](https://github.com/DNSPod/dnspod-sr) is released under BSD license, please see [LICENSE](./LICENSE) for details.

[FasterApple's DNS database](https://github.com/FasterApple/fasterapple) has no copyright and no license.
