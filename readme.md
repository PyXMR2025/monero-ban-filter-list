# Monero Ban Filter List

## This project is temporarily unreliable!

## Overview

This project aims to provide AdGuard Home users with a DNS blocklist to help identify and block known Monero spy nodes. 

These spy nodes may compromise the privacy of Monero users.

## Background

The Monero Research Lab (MRL) recommends that all Monero node operators enable a blocklist of suspicious spy node IP addresses. 

https://github.com/monero-project/research-lab/issues/126

These spy nodes monitor the Monero network by masquerading as numerous independent nodes, which can potentially weaken the privacy protection offered by the Dandelion++ protocol.

## How to Use

### 1. Obtain the Blocklist

The blocklist file is a plain text file (Adblock format) containing IP addresses or domain names to be blocked. 

You can obtain the latest blocklist from the following link:

### 2. Configure in AdGuard Home

1.  Log in to your AdGuard Home administration interface.
2.  Navigate to "Filters" -> "DNS blocklists."
3.  Click "Add blocklist."
4.  Select "Add a custom list."
5.  Enter a descriptive name in the "Name" field, such as "Monero Spy Node Blocklist."
6.  Paste the blocklist URL into the "URL" field.
7.  Click "Save."

AdGuard Home will periodically update this list to ensure your blocklist is up-to-date.

## Contribution

If you discover new spy nodes or have any suggestions for improvement, please contribute by submitting an Issue or a Pull Request.

## License

MIT License

## Source

1.  https://github.com/Boog900/monero-ban-list

## Note

This list can be used with other ad blockers (DNS filters), but its usability is only guaranteed for AdGuard Home.

This list is in "Adblock" format.

This list does not block pure IP spy nodes when AdGuard Home is running.

## Support Me

monero:```876LcATTJR1foWo7XRsEdijZ5357pt4MzBzsx9s4fuEETfnPN6EVUwWCKu5uPJccrhAmTibxuV6WFNzUfgNgBSy29TbbU2c```

## Disclaimer

This list is based on publicly available information and recommendations from the Monero community. While we strive to ensure the accuracy of the list, we cannot guarantee its completeness or timeliness. Use of this list is at your own risk.

This list may inadvertently block some legitimate nodes and domains.

## Signatures

Import the keys and verify the signatures:

```gpg --verify ./pyxmr2025.sig adblock.txt```

You should now see:

gpg: using ED25519 key 724DCCDE543CB6EB1740B11F327E8C5E1416CEF0

gpg: Good signature from "PyXMR2025 ...