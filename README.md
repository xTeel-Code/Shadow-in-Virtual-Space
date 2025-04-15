# Shadow-in-Virtual-Space
This Repo is made for anyone who wants to learn which tools and methods are good for privacy cybersec.

- [[#📧 Temp/Disposable Emails:|📧 Temp/Disposable Emails:]]
- [[#🌐 Browser:|🌐 Browser:]]
- [[#🔍 Search Engine:|🔍 Search Engine:]]
- [[#💻 Operating Systems:|💻 Operating Systems:]]
- [[#💬 Messenger:|💬 Messenger:]]
- [[#🛡️ Anti-Trackers & Scripts:|🛡️ Anti-Trackers & Scripts:]]
	- [[#🛡️ Anti-Trackers & Scripts:#🔰 General Practices:|🔰 General Practices:]]
- [[#📱 Burner Phones|📱 Burner Phones]]
	- [[#📱 Burner Phones#Variant 1: Classic Button Phone|Variant 1: Classic Button Phone]]
	- [[#📱 Burner Phones#Variant 2: Cheap Android + Custom ROM|Variant 2: Cheap Android + Custom ROM]]
	- [[#📱 Burner Phones#⚠️ Extra Paranoia Tips:|⚠️ Extra Paranoia Tips:]]
- [[#💽 Non-network Devices|💽 Non-network Devices]]
	- [[#💽 Non-network Devices#Examples:|Examples:]]
	- [[#💽 Non-network Devices#Setup:|Setup:]]
## 📧 Temp/Disposable Emails:
- **ProtonMail** – Encrypted email service based in Switzerland.
- **Tutanota** – Open-source email with end-to-end encryption.
- **TempMail** – Quick-use disposable email for verification.

## 🌐 Browser:
- **Brave** – Privacy-focused browser with built-in adblock.
- **Firefox (Arkenfox)** – Hardened privacy settings via `arkenfox.js`.
- **LibreWolf** – A Firefox fork focused on privacy, security, and freedom.

## 🔍 Search Engine:
- **DuckDuckGo** – Doesn't track your searches.
- **Mojeek** – Independent crawler and privacy-friendly.
- **Startpage** – Google results but with privacy.

## 💻 Operating Systems:
- **Tails OS** – Live OS aimed at preserving privacy and anonymity.
- **Whonix** – Tor-based OS focused on security.

## 💬 Messenger:
- **Signal** – Encrypted messenger, open-source.
- **Session** – Anonymous, decentralized messaging.

## 🛡️ Anti-Trackers & Scripts:
- **uBlock Origin** – Efficient blocker for ads and trackers.
- **Privacy Badger** – Auto-learns and blocks trackers.
- **NoScript** – Full control of JavaScript execution.

---

# 🛰️ Going Off Grid
### 🔰 General Practices:
- Use a burner phone or non-networked device.
- Disable location and Bluetooth when not needed.
- Be aware of metadata in media and files.

## 📱 Burner Phones
### Variant 1: Classic Button Phone
- Buy a classic phone (no GPS, no apps).
- Pay in **cash**, in-person.
- Buy prepaid SIM (different store, cash, no ID).
- Disable voicemail.
- Power off when unused.
- Use for **outgoing** communication only.
- Do **not** store real names.
- Rules: No use at home, keep in Faraday pouch.
- Extreme case: destroy flash and SIM physically (drill, melt, etc.).

### Variant 2: Cheap Android + Custom ROM
- Buy cheap Android (e.g., Motorola G52). Avoid iPhone/Samsung.
- Flash **GrapheneOS** or **CalyxOS**.
- Never use your home Wi-Fi.
- Don't insert personal SIM.
- Use cash-prepaid SIM.
- Only install essentials: Signal, Session, SimpleX.
- Use PIN – No biometrics.
- Keep GPS, BT, Wi-Fi **off** unless needed.

### ⚠️ Extra Paranoia Tips:
- Wrap in tinfoil if no Faraday pouch.
- Don't use near personal devices – triangulation is real.
- Don't cloud sync or backup.
- No identifying photos.
- If compromised: nuke (drill, microwave, electrocute).

## 💽 Non-network Devices
- Devices **physically** incapable of sending or receiving data.

### Examples:
- Old laptops with Wi-Fi/Ethernet disabled.
- Air-gapped PCs (used in military, cold wallets).
- MP3 players, cameras, retro consoles.

### Setup:
- Wipe data completely.
- Install a secure OS: Tails, Whonix, Qubes, Alpine.
- Remove or disable Wi-Fi card (BIOS or physical removal).
- Never connect to any network.
- Only use trusted USBs – check for hidden files.

---

# 🧾 Awareness of Metadata
- Use **ExifTool** to inspect or remove metadata.
  - [Install ExifTool](https://exiftool.org/install.html)
  - Remove: `exiftool -all:all= -r /path/to/files/`
  - View: `exiftool /path/to/file`

---

# 🧠 Tips and Tricks
- Change IP & MAC addresses regularly.
- Use multiple aliases and devices.
- Avoid repeating patterns (same AP, time, message format).
- Don’t link or reuse accounts.
- Use password manager (**Bitwarden**).
- Don’t reuse photos/text – avoid reverse search.

---

# 🧰 Recommended Tools & Resources
- 🔗 [PrivacyTools.io](https://www.privacytools.io/)
- 📱 [GrapheneOS](https://grapheneos.org/) / [CalyxOS](https://calyxos.org/)
- 🛰️ [Faraday Bags](https://www.amazon.com/s?k=faraday+bag)

---

# 🔍 Security Myths
- **VPN ≠ Anonymity** – It hides your IP but not your identity.
- **Incognito Mode ≠ Private** – It doesn’t stop trackers or hide activity from your ISP.
- **Burner SIMs are trackable** – If patterns are reused or locations overlap.

---

# 🔐 Levels of Paranoia (use based on needs)
- 🔰 **Basic** – Signal, ProtonMail, DuckDuckGo.
- ⚠️ **Intermediate** – Burner phones, non-networked devices.
- 🛡️ **Advanced** – Air-gapped systems, no online presence, physical data destruction.

---

> Stay safe, Stay Sharp. Privacy is not crime🕶️.
