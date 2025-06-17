# `network show`

---

### Command
`network show`

### Function

Displays the current network configuration.

### Example
```
[admin@ssh-to-serial]>network show
Compiled: Jun  8 2025 22:44:07

Static IPv4 Address: 192.0.2.11
IPv4 Subnet Mask: 255.255.255.0
IPv4 Default Gateway: 192.0.2.254
IPv4 Primary DNS: 192.0.2.254
IPv4 Secondary DNS: 192.0.2.254
IPv6 Link-Local Address: fe80::8e12:c2ff:fe00:bb
IPv6 Global Address: 2001:db8::11
IPv6 Default Router: 2001:db8::1
IPv6 Primary DNS: 2001:db8::53
IPv6 Secondary DNS: 2001:db8::54
Reverse SSH Port: 22
Reverse SSH Timeout: 300 seconds
Interface Name: eth0
Hostname: ssh-to-serial
MAC Address: 8C-12-C2-00-00-BB
DHCP: disabled
SLAAC: enabled
Stable Address: enabled with EUI-64
IPv4: enabled
Remote NTP Server: 192.0.2.123
Remote Syslog Server: 192.0.2.12

Current configuration displayed.
```