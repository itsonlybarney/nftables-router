# nftables firewall & router configuration

Configuration files for my RPi network gateway / router. Initially based on the [nftables wiki example](https://wiki.nftables.org/wiki-nftables/index.php/Simple_ruleset_for_a_home_router)

Make nftables run on start-up:
```bash
$ systemctl enable nftables
$ systemctl start nftables
$ systemctl status nftables
```

File location:
```bash
$ nano /etc/nftables.conf
```

Test config file:
```bash
$ nft -f /etc/nftables.conf
$ nft list ruleset
```
---

### Author
[Andrew B](https://nerdgineer.com) - Nerd, engineer, traditional wet shaver
