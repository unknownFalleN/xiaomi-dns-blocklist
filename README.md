# Xiaomi DNS Blocklist

In this repository PiHole DNS blocklists are provided for Xiaomi Devices.

## Getting Started

Just add the raw list(s) in PiHole Settings/Blocklists and click save and update.

### Prerequisites

[PiHole Installation](https://docs.pi-hole.net/main/basic-install/)

## Lists

### xiaomi_dns_block.lst

Manually collected DNS entries from Xiaomi with the help of the community.

### xiaomi_dns_block_with_whitelist.lst

This list contains all domains from the list `xiaomi_dns_block.lst` and `xiaomi_dns_whitelist.lst` also included.

## Whitelist

A collection of domains for the whitelist. These should be set manually in PiHole or use the list `xiaomi_dns_whitelist.lst`

### Xiaomi account management

```html
account.xiaomi.com
```

### System app updater

```html
global.market.xiaomi.com
```

### Find my Device

```html
us.find.api.micloud.xiaomi.net
account.xiaomi.com
find.api.micloud.xiaomi.net
```

### Updates of the Firmware

```html
update.miui.com
update.intl.miui.com
api.io.mi.com
```

## Built With

- With much love and manual collection of the DNS entries  ;)

## Authors

1. **unknownFalleN** - *Initial work and updates* - [unknownFalleN](https://github.com/unknownFalleN)

## License

This project is licensed under the GNU Lesser General Public License v3.0 - see the [LICENSE](https://github.com/unknownFalleN/xiaomi-dns-blocklist/blob/master/LICENSE) file for details.

## Advice

No liability is assumed for completeness and/or correctness.
