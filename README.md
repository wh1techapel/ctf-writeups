<div align="center">

# CTF Write-ups

**Glenvio Regalito Rahardjo** · Cyber Security student, SMK Telkom Purwokerto

Challenge solutions and technical write-ups. Every entry documents the approach, not
just the flag, including the ones that took several wrong turns first.

[Portfolio](https://github.com/wh1techapel/cybersecurity-portfolio) · [CyberAtlas knowledge base](https://github.com/wh1techapel/CyberAtlas) · [Profile](https://github.com/wh1techapel)

</div>

---

## picoCTF

### Cryptography

| Challenge | Topic | Write-up |
| :--- | :--- | :--- |
| [HideToSee](picoCTF/cryptography/HideToSee/) | Steganography (steghide) + Atbash cipher | [script](picoCTF/cryptography/HideToSee/solve_atbash.py) · [PDF](picoCTF/cryptography/HideToSee/HideToSeePicoCTF.pdf) |
| [Sum-O-Primes](picoCTF/cryptography/Sum-O-Primes/) | RSA with leaked sum of primes | [script](picoCTF/cryptography/Sum-O-Primes/solve_sum_o_primes.py) · [PDF](picoCTF/cryptography/Sum-O-Primes/Sum-O-Primes_Writeup.pdf) |

### Reverse Engineering

| Challenge | Topic | Write-up |
| :--- | :--- | :--- |
| [B1ll_Gat35](picoCTF/reverse-engineering/B1ll_Gat35/) | Windows PE32 executable analysis | [PDF](picoCTF/reverse-engineering/B1ll_Gat35/B1ll_Gat35_Writeup.pdf) |
| [TapIntoHash](picoCTF/reverse-engineering/TapIntoHash/) | Reversing a block-chain hash routine | [script](picoCTF/reverse-engineering/TapIntoHash/decrypted_plaintext.py) · [PDF](picoCTF/reverse-engineering/TapIntoHash/TapIntoHash_WriteUp.pdf) |
| [reverse_cipher](picoCTF/reverse-engineering/reverse_chiper/) | ELF 64-bit cipher reversing | [script](picoCTF/reverse-engineering/reverse_chiper/decrypt_flag.py) · [PDF](picoCTF/reverse-engineering/reverse_chiper/reverse_cipher_Writeup.pdf) |
| [weirdsnake](picoCTF/reverse-engineering/weirdsnake/) | Python bytecode disassembly | [script](picoCTF/reverse-engineering/weirdsnake/key.py) · [PDF](picoCTF/reverse-engineering/weirdsnake/WeirdSnake_WriteUp.pdf) |

### Web Exploitation

| Challenge | Topic | Write-up |
| :--- | :--- | :--- |
| [Trickster](picoCTF/web-exploitation/Trickster/) | Web exploitation | [PDF](picoCTF/web-exploitation/Trickster/Trickster_writeup.pdf) |
| [byp4ss3d](picoCTF/web-exploitation/byp4ss3d/) | Access-control bypass (`.htaccess`) | [PDF](picoCTF/web-exploitation/byp4ss3d/byp4ss3d_picoCTF_writeup.pdf) |
| [head-dump](picoCTF/web-exploitation/head-dump/) | Information disclosure via heap/head dump | [PDF](picoCTF/web-exploitation/head-dump/head-dump_Writeup.pdf) |

## Hack The Box — Starting Point

| Tier | Machines |
| :--- | :--- |
| [Tier 0](HackTheBox/Starting-Point/Tier-0/) | Meow · Fawn · Dancing · Redeemer |
| [Tier 1](HackTheBox/Starting-Point/Tier-1/) | Appointment · Crocodile · Responder · Sequel · Three |
| [Tier 2](HackTheBox/Starting-Point/Tier-2/) | Archetype |

Each machine has a PDF write-up covering enumeration, foothold, and privilege escalation.

## Competitions

| Event | Year | Write-up |
| :--- | :--- | :--- |
| [CSSC DIY (Amikom Yogyakarta)](CSSC-DIY-2025/) | 2025 | [document](CSSC-DIY-2025/WU_CSSC2025JOGJA.docx) |
| [Cyber Jawara](CYBER-JAWARA/) | 2025 | [document](CYBER-JAWARA/WRITEUP_CYBERJAWARA_2025_SMKTELKOM-PURWOKERTO.docx) |

---

## Tools commonly used

`nmap` · `Burp Suite` · `ffuf` · `gobuster` · `steghide` · `GDB` · `pwntools` · `Python`

## Disclaimer

All challenges were solved on authorized CTF platforms and practice labs. These notes are
for education only.
