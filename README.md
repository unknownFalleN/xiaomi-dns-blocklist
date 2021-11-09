# Xiaomi DNS Blocklist

In this repository PiHole DNS blocklists are provided for Xiaomi Devices.

## Getting Started

Just add the raw list(s) in PiHole Settings/Blocklists and click save and update.

### Prerequisites

[PiHole Installation](https://docs.pi-hole.net/main/basic-install/)

## Lists

### xiaomi_dns_block.lst

Manually collected DNS entries from Xiaomi  with the help of the community. Removed battery killig domains for mobiles.

### sublert lists

Automatically generated list using [Sublert](https://github.com/yassineaboukir/sublert). This list contains all subdomains with TLS certificates from Xiaomi.com and mi.com. **These lists cannot be used directly in pihole.**

## Whitelist

A collection of domains for the whitelist. These should be set manually in PiHole.

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
```

## Built With

- With much love and manual collection of the DNS entries  ;)
- [Sublert](https://github.com/yassineaboukir/sublert) - Sublert is a security and reconnaissance tool that was written in Python to leverage certificate transparency for the sole purpose of monitoring new subdomains deployed by specific organizations and issued TLS/SSL certificate.

## Authors

1. **unknownFalleN** - *Initial work and updates* - [unknownFalleN](https://github.com/unknownFalleN)

## License

This project is licensed under the GNU Lesser General Public License v3.0 - see the [LICENSE](https://github.com/unknownFalleN/xiaomi-dns-blocklist/blob/master/LICENSE) file for details.

## Advice

No liability is assumed for completeness and/or correctness.
