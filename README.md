# Xiaomi DNS Blocklist

In this repository PiHole DNS blocklists are provided for Xiaomi Devices.

## Getting Started

Just add the raw list(s) in PiHole Settings/Blocklists and click save and update.

### Prerequisites

[PiHole Installation](https://docs.pi-hole.net/main/basic-install/)

### Lists

#### xiaomi_dns_block.lst

Manually collected DNS entries from Xiaomi  with the help of the community. Removed battery killig domains for mobiles.

#### xiaomi.com.txt

Automatically generated list using [Sublert](https://github.com/yassineaboukir/sublert). This list contains all subdomains with TLS certificates from Xiaomi.com. This list can be used to block all subdomains of Xiaomi.

## Built With

* With much love and manual collection of the DNS entries  ;)
* [Sublert](https://github.com/yassineaboukir/sublert) - Sublert is a security and reconnaissance tool that was written in Python to leverage certificate transparency for the sole purpose of monitoring new subdomains deployed by specific organizations and issued TLS/SSL certificate.

## Authors

* **unknownFalleN** - *Initial work* - [unknownFalleN](https://github.com/unknownFalleN)

## License

This project is licensed under the GNU Lesser General Public License v3.0 - see the [LICENSE](https://github.com/unknownFalleN/xiaomi-dns-blocklist/blob/master/LICENSE) file for details

## Advice

No liability is assumed for completeness and/or correctness.
