# AllStar Presentation

A presentation about AllStar for amateur radio.

**This presentation is currently under development.**

[View the main presentation](https://jchonig.github.io/pres-allstar/) — [View the Hotspot presentation](https://jchonig.github.io/pres-allstar/hotspot.html)

## Outline

1. What is AllstarLink?
2. History / Background
3. Compare to EchoLink and IRLP
4. AllstarLink Network (US node map)
5. Uses
   - Hotspot
   - Linking repeaters
   - Conference bridges / hubs (radioless nodes)
   - Remote base (including access to a remote repeater)
6. Node Types (diagram: Hotspot, Radio, Repeater, Conference Bridge)
7. Uses in Practice (nets, remote access, EmComm, Skywarn, club, portable, monitoring)
8. Hubs and Nets (equivalent to Wires-X rooms/nodes)
9. A Hub Network: HubNet UK (node connection map)
10. Architecture (Servers, Nodes, how they connect, simpleusb vs. usbradio)
    - simpleusb vs. usbradio (detail slide)
11. Addressing (5 and 6 digit node numbers)
11. Hardware
    - Server Hardware
    - Sound Cards and Interfaces (DigiRig, TOADS, AIOC, URI, CM108)
    - Radios and All-in-One (HotspotRadioUSB)
12. Software (ASL3, HamVoip)
13. Setting Up AllstarLink (overview: sign up → approval → login → NNX → server → node)
    - Login: Account Settings (Portal_Account_settings.png)
    - Add a Server: Server List (Portal_Servers.png)
    - Add a Server: Server Settings (Portal_Server.png)
    - Add a Node: Node List (Portal_Nodes.png)
    - Add a Node: Node Settings (Portal_Node.png)
14. Installing ASL3 (link to Pi appliance detailed install guide)
15. Connecting to Your Node (nodeNNNNNN.local, Allstar-Web-main.png)
16. Web Admin Portal (based on Cockpit, cockpit-project.org)
    - Web Admin Portal: Login (Allstar-Cockpit-Login.png, use image credentials)
    - Web Admin Portal: Enable Administrative Access (Allstar-Cockpit-Limited.png + Allstar-Cockpit-Access.png)
    - Web Admin Portal: Terminal (Allstar-Cockpit-Terminal.png)
    - Setting Up Allmon3 Credentials (sudo allmon3-passwd, systemctl restart allmon3)
17. Node Configuration (asl-menu, Freddie Mac YouTube video, ASL3 Menu docs)
16. DTMF Commands
14. Linking to EchoLink (addressing: 3 + 6-digit zero-padded node number)
15. Digital Radio Integration (DVSwitch: DMR, D-STAR, YSF, P25, NXDN)
16. Monitoring (allmon3, supermon-ng)
17. Demo a hotspot
18. Radioless Node (AllScan UCI80M + Motorola M1 speaker-mic + RPi; M1 vs K1 audio quality; link to Random Wire #180)
19. Etiquette (listen before connecting, ID yourself, disconnect cleanly, etc.; link to Ham Radio Crusader Ep. 1)
20. Other Projects — Ampersand (KC1FSZ): Asterisk-free AllStar linking, HD audio, browser config, GPL)
21. Getting Started (overview: account → server → node)
    - Step 1: Register an Account (license upload, email validation)
    - Step 2: Register a Server (location, IAX port UDP 4569)
    - Step 3: Request a Node Number (auto-approved, get number + password)
    - 6-Digit Node Numbers / NNX (extends 5-digit to 6-digit, unlocks 9 additional nodes)
22. Resources (software/community + hardware, combined)
23. Questions / 73

---

## [Setting up a Hotspot](https://jchonig.github.io/pres-allstar/hotspot.html) *(Draft)*

1. Title — Setting up a Hotspot (N2VLV)
2. What is an AllStar Hotspot? (low-power FM radio bridging RF to internet via AllStar)
3. Pre-Assembled Hotspots (intro slide)
4. SHARI PiZero — kits4hams.com/shari-pizero — $205 assembled (Pi Zero 2W + SA818)
5. HotSpotRadio — hotspotradios.com/hotspotradio — $298 + $18 shipping (Pi 3B + SA818 PiHat)
6. ClearNode — node-ventures.com/buy-clearnode/ — $495 (AllStar + EchoLink + digital + mobile app)
7. Micro-Node Nano-AE-M1 — micro-node.com/nano-ae-m1.shtml — $495+ (LCD touchscreen, standalone)
8. AllScan Complete Nodes — allscan.info/products/ — $229 and up (half-duplex, full-duplex, radio-less; ASL3 pre-configured)
9. Building a Hotspot (Pi Zero 2W, Pi 3B+, or Pi 4 + radio interface + ASL3)
10. Radio Interfaces (comparison table)
    - HotSpotRadio-USB — $98 + shipping (USB dongle, self-contained)
    - SHARI PiXX — $80 kit / $105 assembled (Pi3/Pi4 USB module)
    - SHARI PiHat — $235+ assembled (Pi4 HAT, metal case)
    - SHARI PiZero — $100 kit / $205 assembled
    - AURSINC Pi Hat — ~$69 (SA-818 compatible HAT)
11. Storage: High-Endurance SD Card (Samsung PRO Endurance or SanDisk High Endurance, 32 GB)
12. Building a Node (placeholder — ASL3 Pi Appliance image, Cockpit config, asl-menu)
13. Softphones
    - RepeaterPhone (iOS)
    - Tranceive (macOS)
    - Android — QSO One (qso1.net) coming
    - Windows — QSO One coming
14. Questions / 73
