# MPPM Project: Libra

Libra supports only [RainBoard](https://github.com/trieuthanhnc/MPPM-RainBoard)

A backend framework based on Xray, supporting Vmess, Vless, Trojan, and Shadowsocks protocols.

If you like this project, you can click the star and view in the upper right corner to track the progress of this project.

## Featured

- Supports multiple protocols Vmess, Vless, Trojan, Shadowsocks.
- Supports single connection to multiple boards and nodes without rebooting.
- Online IP support is limited
- Support user level rate limit.
- Simple and clear configuration.
- Automatically restart when modifying files in the configuration directory.
- Easy to compile and upgrade, can quickly update core version, support new Xray-core features.
- Support UDP and many other functions

## Special

| Special                     | Vmess | Vless | Trojan | Shadowsocks |
| --------------------------- | ----- | ----- | ------ | ----------- |
| Get node informatio         | √     | √     | √      | √           |
| Node status report          | √     | √     | √      | √           |
| Get user information        | √     | √     | √      | √           |
| User traffic report         | √     | √     | √      | √           |
| User online IP report       | √     | √     | √      | √           |
| User online IP restrictions | √     | √     | √      | √           |
| User speed limit            | √     | √     | √      | √           |
| Number of people online     | √     | √     | √      | √           |
| Audit rules                 | √     | √     | √      | √           |
| Custom DNS                  | √     | √     | √      | √           |

## Panel support

| Panel     | Vmess | Vless | Trojan | Shadowsocks |
| --------- | ----- | ----- | ------ | ----------- |
| RainBoard | √     | √     | √      | √           |

## Install

```
bash <(curl -Ls https://raw.githubusercontent.com/trieuthanhnc/MPPM-Libra-Release/master/install.sh)
```

`--version %` - Version flag, replace the value into the character **%**. The desired version for installation (default: **latest**). Refer to the version at: [https://github.com/trieuthanhnc/MPPM-Libra/releases](https://github.com/trieuthanhnc/MPPM-Libra/releases)

## Update

```
bash <(curl -Ls https://raw.githubusercontent.com/trieuthanhnc/MPPM-Libra-Release/master/update.sh)
```

`--version %` - Version flag, replace the value into the character **%**. The desired version for installation (default: **latest**). Refer to the version at: [https://github.com/trieuthanhnc/MPPM-Libra/releases](https://github.com/trieuthanhnc/MPPM-Libra/releases)

## Uninstall

```
bash <(curl -Ls https://raw.githubusercontent.com/trieuthanhnc/MPPM-Libra-Release/master/uninstall.sh)
```

## Support

Email: [trieuthanhnc@gmail.com](mailto:trieuthanhnc@gmail.com)

Telegram: [@trieuthanhnc](https://t.me/trieuthanhnc)
