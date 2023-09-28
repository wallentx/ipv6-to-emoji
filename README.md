# ipv6-to-emoji
```bash
Usage: ipv6-to-emoji [OPTIONS] [INPUT_DATA]

  Convert IPv6 addresses to emojis and vice versa.

Options:
  -e, --encode   Encode an IPv6 address to emoji.
  -d, --decode   Decode an emoji string to IPv6 address.
  -v, --verbose  Display detailed output.
  -h, --help     Show this message and exit.
```
---

```console
cool_user@ARCH-LINUX:~$ ipv6-to-emoji -e 2606:4700:0000:0000:6812:176c
👶💡🐯🍈🚻😀🍑👴😖❤

cool_user@ARCH-LINUX:~$ ipv6-to-emoji -d 👶💡🐯🍈🚿😀🍑👴😖❤
2606:4700::6812:176C
```
