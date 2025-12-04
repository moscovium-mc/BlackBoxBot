# BlackBoxBot

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![TypeScript](https://img.shields.io/badge/typescript-5.0+-blue.svg)](https://www.typescriptlang.org/)
[![Node.js](https://img.shields.io/badge/node.js-18.0+-green.svg)](https://nodejs.org/)
[![Discord.js](https://img.shields.io/badge/discord.js-v14-blue.svg)](https://discord.js.org/)
[![Platform](https://img.shields.io/badge/platform-linux%20%7C%20macos%20%7C%20windows-lightgrey.svg)]()

[![GitHub Stars](https://img.shields.io/github/stars/moscovium-mc/BlackBoxBot?style=social)](https://github.com/moscovium-mc/BlackBoxBot/stargazers)
[![Forks](https://img.shields.io/github/forks/moscovium-mc/BlackBoxBot?style=social)](https://github.com/moscovium-mc/BlackBoxBot/network/members)
[![Issues](https://img.shields.io/github/issues/moscovium-mc/BlackBoxBot)](https://github.com/moscovium-mc/BlackBoxBot/issues)

> **⭐ Star this repo to get notified when the code drops!**

Cybersecurity utilities Discord bot with 25 commands for network recon, crypto operations, and OSINT. Built for security researchers, penetration testers, and CTF participants.

**Full documentation:** https://blackboxbot-docs.netlify.app/

---

## Status

Code coming soon. Currently testing before initial release.

## Features

- **25 slash commands** across 4 categories
- **Network Utilities (9)** - ICMP ping, WHOIS, DNS enumeration, IP geolocation, port scanning, HTTP headers, SSL/TLS inspection, subnet calculations, MAC vendor lookup
- **Cryptographic Operations (7)** - Hash generation, Base64, JWT decoding, password generation, ROT13, URL encoding, timestamp conversion
- **OSINT Tools (7)** - QR codes, VirusTotal, user agents, breach checking (HIBP), data extraction, URL parsing, Shodan search
- **Meta Commands (2)** - Help and about
- **TypeScript + Discord.js v14** - Full type safety
- **Cross-platform** - Linux, macOS, Windows/WSL2

## Quick Start

```bash
# Clone repository
git clone https://github.com/moscovium-mc/BlackBoxBot.git
cd BlackBoxBot

# Install dependencies
npm install

# Configure environment
cp .env.example .env
# Edit .env with your Discord bot credentials

# Build and deploy
npm run build
npm run deploy

# Start bot
npm start
```

## Platform Support

| Platform | Commands Working |
|----------|------------------|
| Linux    | 25/25 (100%)     |
| macOS    | 25/25 (100%)     |
| Windows  | 16/25 (64%)      |
| WSL2     | 25/25 (100%)     |

Windows requires WSL2 or additional utilities for full network command support.

## Documentation

**Complete documentation available at:** https://blackboxbot-docs.netlify.app/

- [Installation Guide](https://blackboxbot-docs.netlify.app/#installation)
- [Discord Bot Setup](https://blackboxbot-docs.netlify.app/#discord-setup)
- [Command Reference](https://blackboxbot-docs.netlify.app/#network)
- [Deployment Options](https://blackboxbot-docs.netlify.app/#deployment)
- [API Keys Configuration](https://blackboxbot-docs.netlify.app/#api-keys)
- [Troubleshooting](https://blackboxbot-docs.netlify.app/#troubleshooting)

## Support

If you find this project useful, consider supporting my work:

<a href="https://buymeacoffee.com/webmoney" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" height="40"></a>

**Crypto donations:**
- <a href="bitcoin:bc1quavqz6cxqzfy4qtvq4zxc4fjgap3s7cmxja0k4"><img src="https://img.shields.io/badge/Bitcoin-000000?style=plastic&logo=bitcoin&logoColor=white" alt="Bitcoin"></a> `bc1quavqz6cxqzfy4qtvq4zxc4fjgap3s7cmxja0k4`
- <a href="ethereum:0x5287af72afbc152b09b3bf20af3693157db9e425"><img src="https://img.shields.io/badge/Ethereum-627EEA?style=plastic&logo=ethereum&logoColor=white" alt="Ethereum"></a> `0x5287af72afbc152b09b3bf20af3693157db9e425`
- <a href="solana:HYZjfEx8NbEMJX1vL1GmGj39zA6TgMsHm5KCHWSZxF4j"><img src="https://img.shields.io/badge/Solana-9945FF?style=plastic&logo=solana&logoColor=white" alt="Solana"></a> `HYZjfEx8NbEMJX1vL1GmGj39zA6TgMsHm5KCHWSZxF4j`
- <a href="monero:86zv6vTDuG35sdBzBpwVAsD71hbt2gjH14qiesyrSsMkUAWHQkPZyY9TreeQ5dXRuP57yitP4Yn13SQEcMK4MhtwFzPoRR1"><img src="https://img.shields.io/badge/Monero-FF6600?style=plastic&logo=monero&logoColor=white" alt="Monero"></a> `86zv6vTDuG35sdBzBpwVAsD71hbt2gjH14qiesyrSsMkUAWHQkPZyY9TreeQ5dXRuP57yitP4Yn13SQEcMK4MhtwFzPoRR1`

## Legal Disclaimer

**READ THIS BEFORE USING**

**This tool is for authorized security research and educational purposes ONLY.**

By using BlackBoxBot, you acknowledge that:

1. **Authorized Use Only:**
   - You will only use network commands on systems you own or have explicit written permission to test
   - You are conducting authorized security research or penetration testing
   - You will comply with all applicable laws and regulations

2. **Prohibited Activities:**
   - Unauthorized port scanning or network reconnaissance
   - Unauthorized vulnerability testing or exploitation
   - Any malicious or illegal activities
   - Violating Discord Terms of Service

3. **Legal Compliance:**
   - You will comply with all applicable laws including CFAA (18 U.S.C. § 1030), Computer Misuse Act, and similar legislation
   - You understand that unauthorized access to computer systems is illegal
   - You will obtain proper authorization before testing any systems

4. **Liability:**
   - The author provides NO WARRANTIES and accepts NO LIABILITY for misuse
   - Users assume ALL RESPONSIBILITY for their actions
   - This tool is provided "AS IS" without warranty of any kind

**Unauthorized network scanning or system access is illegal. If you don't have permission, don't use these commands.**

## Responsible Use Guidelines

**DO:**
- Only scan/test systems you own or have written permission to access
- Use for authorized penetration testing engagements
- Conduct ethical security research
- Follow responsible disclosure practices
- Respect API rate limits and terms of service

**DON'T:**
- Scan systems without authorization
- Use for malicious purposes
- Harass or spam other users
- Violate Discord Terms of Service
- Share or use credentials without permission

## Ethical Considerations

This tool exists to:
- Support authorized security testing and research
- Provide educational resources for learning cybersecurity
- Enable rapid-access tooling in collaborative environments
- Demonstrate practical applications of security concepts

Use it responsibly. Security research should make the internet safer, not more dangerous.

## Contributing

Contributions are welcome!

## License

MIT License - See LICENSE file for details.

**Use responsibly. Unauthorized access to computer systems is illegal.**

---

Built by [moscovium-mc](https://github.com/moscovium-mc)

**Disclaimer:** BlackBoxBot is a security research tool. The developers are not responsible for any misuse or damage caused by this tool. Always obtain proper authorization before conducting security research.
