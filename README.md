# Jarkom-Modul-4-B26-2023

Anggota Kelompok 

|   Nama                             | NRP      |
| ------                             | ------   |
|  Nur Azizah                        |5025211252|
|  Rayhan Almer Kusumah              |5025211115|
|  Faiz Haq Noviandra Ciptadi Putra  |5025211132|

## Topologi PKT VLSM
![Screenshot 2023-12-06 135429](https://github.com/Dancingaroundthelies/Jarkom-Modul-4-B26-2023/assets/91133817/d9fbb8e3-51aa-41f6-9b90-e53e14432a3a)

## Topologi GNS3 CIDR
![Screenshot 2023-12-06 164421](https://github.com/Dancingaroundthelies/Jarkom-Modul-4-B26-2023/assets/91133817/6f7660b4-3d93-4b64-9b9d-049b23758f91)

## Rute
Hasil rute yang kami dapatkan adalah sebagian berikut
![Screenshot 2023-12-06 164700](https://github.com/Dancingaroundthelies/Jarkom-Modul-4-B26-2023/assets/91133817/1456b269-fde3-4beb-bfd2-0a21bea05514)

## VSLM 

### Pembagian IP

### Konfigurasi Network
- RoyalCapital (63 Host)

```
#A1
auto eth0
iface eth0 inet static
address 192.191.8.5
netmask 255.255.255.0
gateway 192.191.8.1
```

- WilleRegion (63 Host)

```
#A1
auto eth0
iface eth0 inet static
address 192.191.8.10
netmask 255.255.255.0
gateway 192.191.8.1
```

- Denken 

```
auto lo
iface lo inet loopback

#A2
auto eth0
iface eth0 inet static
address 192.191.7.106
netmask 255.255.255.252
gateway 192.191.7.105

#A1
auto eth1
iface eth1 inet static
address 192.191.8.1
netmask 255.255.255.0
```

- Aura 

```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet dhcp

#A20
auto eth1
iface eth1 inet static
address 192.191.7.141
netmask 255.255.255.252

#A2
auto eth2
iface eth2 inet static
address 192.191.7.105
netmask 255.255.255.252

#A3
auto eth3
iface eth3 inet static
address 192.191.7.109
netmask 255.255.255.252
```

- Frieren 

```
auto lo
iface lo inet loopback

#A20
auto eth0
iface eth0 inet static
address 192.191.7.142
netmask 255.255.255.252
gateway 192.191.7.141

#A19
auto eth1
iface eth1 inet static
address 192.191.7.137
netmask 255.255.255.252

#A21
auto eth2
iface eth2 inet static
address 192.191.7.161
netmask 255.255.255.224
```

- LakeKorridor (24 Host)

```
#A21
auto eth0
iface eth0 inet static
address 192.191.7.165
netmask 255.255.255.224
gateway 192.191.7.161
```

- Flamme 

```
auto lo
iface lo inet loopback

#A19
auto eth0
iface eth0 inet static
address 192.191.7.138
netmask 255.255.255.252
gateway 192.191.7.137

#A14
auto eth1
iface eth1 inet static
address 192.191.7.129
netmask 255.255.255.252

#A16
auto eth2
iface eth2 inet static
address 192.191.20.1
netmask 255.255.252.0

#A17
auto eth3
iface eth3 inet static
address 192.191.7.133
netmask 255.255.255.252
```

- Fern 

```
auto lo
iface lo inet loopback

#A17
auto eth0
iface eth0 inet static
address 192.191.7.134
netmask 255.255.255.252
gateway 192.191.7.133

#A18
auto eth1
iface eth1 inet static
address 192.191.24.1
netmask 255.255.248.0
```

- LaubHills (397 Host)

```
auto eth0
iface eth0 inet static
address 192.191.25.5
netmask 255.255.248.0
gateway 192.191.24.1
```

- AppetitRegion (625 Host)

```
auto eth0
iface eth0 inet static
address 192.191.25.10
netmask 255.255.248.0
gateway 192.191.24.1
```

- RohrRoad (1000 Host)

```
#A16
auto eth0
iface eth0 inet static
address 192.191.20.5
netmask 255.255.252.0
gateway 192.191.20.1
```

- Himmel 

```
auto lo
iface lo inet loopback

#A14
auto eth0
iface eth0 inet static
address 192.191.7.130
netmask 255.255.255.252
gateway 192.191.7.129

#A13
auto eth1
iface eth1 inet static
address 192.191.7.145
netmask 255.255.255.248
```

- ShcwerMountains (5 Host)

```
auto eth0
iface eth0 inet static
address 192.191.7.147
netmask 255.255.255.248
gateway 192.191.7.145
```

- Eisen 

```
auto lo
iface lo inet loopback

#A3
auto eth0
iface eth0 inet static
address 192.191.7.110
netmask 255.255.255.252
gateway 192.191.7.109

#A15
auto eth1
iface eth1 inet static
address 192.191.7.153
netmask 255.255.255.248

#A4
auto eth2
iface eth2 inet static
address 192.191.7.113
netmask 255.255.255.252

#A5
auto eth3
iface eth3 inet static
address 192.191.7.117
netmask 255.255.255.252

#A8
auto eth4
iface eth4 inet static
address 192.191.7.121
netmask 255.255.255.252
```

- Stark 

```
auto eth0
iface eth0 inet static
address 192.191.7.114
netmask 255.255.252.0
gateway 192.191.7.113
```

- Lugner 

```
auto lo
iface lo inet loopback

#A5
auto eth0
iface eth0 inet static
address 192.191.7.118
gateway 192.191.7.117
netmask 255.255.255.252

#A6
auto eth1
iface eth1 inet static
address 192.191.12.1
netmask 255.255.252.0

#A7
auto eth2
iface eth2 inet static
address 192.191.9.1
netmask 255.255.255.0
```

- TurkRegion (1000 Host)

```
auto eth0
iface eth0 inet static
address 192.191.12.5
netmask 255.255.252.0
gateway 192.191.12.1
```

- GrobeForest (250 Host)

```
auto eth0
iface eth0 inet static
address 192.191.9.5
netmask 255.255.255.0
gateway 192.191.9.1
```

- Richter 

```
auto eth0
iface eth0 inet static
address 192.191.7.154
netmask 255.255.252.0
gateway 192.191.7.153
```

- Revolte

```
auto eth0
iface eth0 inet static
address 192.191.7.155
netmask 255.255.252.0
gateway 192.191.7.153
```

- Linie 

```
auto lo
iface lo inet loopback

#A8
auto eth0
iface eth0 inet static
address 192.191.7.122
gateway 192.191.7.121
netmask 255.255.255.252

#A9
auto eth1
iface eth1 inet static
address 192.191.10.1
netmask 255.255.254.0

#A10
auto eth2
iface eth2 inet static
address 192.191.7.125
netmask 255.255.255.252
```

- GranzChannel (254 Host)

```
auto eth0
iface eth0 inet static
address 192.191.10.5
netmask 255.255.254.0
gateway 192.191.10.1
```

- Lawine 

```
auto lo
iface lo inet loopback

#A10
auto eth0
iface eth0 inet static
address 192.191.7.126
netmask 255.255.255.252
gateway 192.191.7.125

#A11
auto eth1
iface eth1 inet static
address 192.191.7.193
netmask 255.255.255.192
```

- BredtRegion (29 Host)

```
auto eth0
iface eth0 inet static
address 192.191.7.197
netmask 255.255.255.192
gateway 192.191.7.193
```

- Heiter 

```
auto lo
iface lo inet loopback

#A11
auto eth0
iface eth0 inet static
address 192.191.7.222
netmask 255.255.255.192
gateway 192.191.7.193

#A12
auto eth1
iface eth1 inet static
address 192.191.16.1
netmask 255.255.252.0
```

- Sein 

```
auto eth0
iface eth0 inet static
address 192.191.16.2
netmask 255.255.252.0
gateway 192.191.16.1
```

- RiegelCanyon (510 Host)

```
auto eth0
iface eth0 inet static
address 192.191.16.7
netmask 255.255.252.0
gateway 192.191.16.1
```

### Routing
- Denken 

```
up route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.191.7.105
```

- Lugner 

```
up route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.191.7.110
```

- Linie 

```
up route add -net 192.191.7.192 netmask 255.255.255.192 gw 192.191.7.126
up route add -net 192.191.16.0 netmask 255.255.252.0 gw 192.191.7.126
```

- Lawine 

```
up route add -net 192.191.16.0 netmask 255.255.252.0 gw 192.191.7.222
```

- Heiter

```
up route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.191.7.126
```

- Himmel 

```
up route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.191.7.138
```

- Flamme 

```
up route add -net 192.191.24.0 netmask 255.255.248.0 gw 192.191.7.134
up route add -net 192.191.7.144 netmask 255.255.255.248 gw 192.191.7.130
```

- Fern 

```
up route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.191.7.138
```

- Frieren

```
up route add -net 192.191.7.132 netmask 255.255.255.252 gw 192.191.7.138
up route add -net 192.191.24.0 netmask 255.255.248.0 gw 192.191.7.138
up route add -net 192.191.20.0 netmask 255.255.252.0 gw 192.191.7.138
up route add -net 192.191.7.128 netmask 255.255.255.252 gw 192.191.7.138
up route add -net 192.191.7.144 netmask 255.255.255.248 gw 192.191.7.138
```

- Eisen 

```
up route add -net 192.191.12.0 netmask 255.255.252.0 gw 192.191.7.118
up route add -net 192.191.9.0 netmask 255.255.255.0 gw 192.191.7.118

up route add -net 192.191.10.0 netmask 255.255.254.0 gw 192.191.7.122
up route add -net 192.191.7.124 netmask 255.255.255.252 gw 192.191.7.122
up route add -net 192.191.7.192 netmask 255.255.255.192 gw 192.191.7.122
up route add -net 192.191.16.0 netmask 255.255.252.0 gw 192.191.7.122
```

- Aura 

```
# Frieren
up route add -net 192.191.7.160 netmask 255.255.255.224 gw 192.191.7.142
up route add -net 192.191.7.136 netmask 255.255.255.252 gw 192.191.7.142
up route add -net 192.191.7.132 netmask 255.255.255.252 gw 192.191.7.142
up route add -net 192.191.24.0 netmask 255.255.248.0 gw 192.191.7.142
up route add -net 192.191.20.0 netmask 255.255.252.0 gw 192.191.7.142
up route add -net 192.191.7.128 netmask 255.255.255.252 gw 192.191.7.142
up route add -net 192.191.7.144 netmask 255.255.255.248 gw 192.191.7.142

# Denken
up route add -net 192.191.8.0 netmask 255.255.255.0 gw 192.191.7.106

# Eisen
up route add -net 192.191.7.112 netmask 255.255.255.252 gw 192.191.7.110
up route add -net 192.191.7.116 netmask 255.255.255.252 gw 192.191.7.110
up route add -net 192.191.12.0 netmask 255.255.252.0 gw 192.191.7.110
up route add -net 192.191.9.0 netmask 255.255.255.0 gw 192.191.7.110
up route add -net 192.191.7.120 netmask 255.255.255.252 gw 192.191.7.110
up route add -net 192.191.10.0 netmask 255.255.254.0 gw 192.191.7.110
up route add -net 192.191.7.124 netmask 255.255.255.252 gw 192.191.7.110
up route add -net 192.191.7.192 netmask 255.255.255.192 gw 192.191.7.110
up route add -net 192.191.16.0 netmask 255.255.252.0 gw 192.191.7.110
up route add -net 192.191.7.152 netmask 255.255.255.248 gw 192.191.7.110
```


## VLSM
![Screenshot 2023-12-06 163555](https://github.com/Dancingaroundthelies/Jarkom-Modul-4-B26-2023/assets/91133817/fe9b6631-7aa4-46d6-91d8-589534b72e2a)

