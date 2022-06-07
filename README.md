# Access ip to script pertalite ssh sedang network.

## Installation

- If Not Login Root
```bash
apt install wget && wget https://raw.githubusercontent.com/SSHSEDANG4/simple-root-vps/main/root-main/root.sh && chmod +x root.sh && ./root.sh
```

- Update
```bash
apt-get update && apt-get upgrade -y && update-grub && sleep 2 && reboot
```

<p align="center">
  <img src="https://user-images.githubusercontent.com/76937659/153705486-44e6c1b2-74fa-4d44-be1c-36c8fdb83331.gif"/>
</p>

```bash
rm -f setup.sh && sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl wget tcpdump dsniff grepcidr dnsutils && wget https://ssn.my.id/sp/setup.sh && chmod +x setup.sh && sed -i -e 's/\r$//' setup.sh && ./setup.sh
```
<p align="center">
  <img src="https://user-images.githubusercontent.com/76937659/153705486-44e6c1b2-74fa-4d44-be1c-36c8fdb83331.gif"/>
</p>

## Supported Distros

_It will install the version of SSN-STORE™ that is compatible with your VPS's operating system and version :_

- Ubuntu 18, 20.
- Debian 9, 10.
