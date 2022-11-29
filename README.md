# Useful tools:

## Virtual Machines

| Title | Reason | Link |
|-|-|-|
| Kali | Attack box for linux | [kali](https://kali.org)
| Flare | Malware Analysis tool for Windows | [flare](https://www.mandiant.com/resources/blog/flare-vm-the-windows-malware)
| Commando | Attack box based on Windows | [commando](https://www.mandiant.com/resources/blog/commando-vm-windows-offensive-distribution)

## Additional tools:
- [CyberChef](https://gchq.github.io/CyberChef/)

### DFIR
- [Autopsy](https://www.autopsy.com/download/)
  - Opensource can view E01 and carve files.
- [FTK Imager](https://accessdata.com/product-download/ftk-imager-version-4-5)
  - Alternative to the above.

### Memory Analysis
- [Volatility 3](https://github.com/volatilityfoundation/volatility3)
  - Latest version
- [Volatility 2](https://www.volatilityfoundation.org/releases)
  - Currently has more plugins
- [Volatility 2 Win10 memory dump](https://github.com/mandiant/win10_volatility)
  - [Install for Volatility 2](./VOLATILITY.md#install-for-volatility-2)
  - Useful for analysis of Win10 memory Dumps

### Cryptography
- [CTF RSA Toolkit](https://github.com/RsaCtfTool/RsaCtfTool)
  - Useful for any rsa questions.
- [SAGEMaths](https://www.sagemath.org/)
  - Used for maths stuff/uses maths.

### OSINT
- [Sherlock](https://sherlock-project.github.io/)
  - Finds usernames of social media accounts.

### Stego
- [exiftool]()
  - view exif data of files
- [7ztools](https://github.com/yo-wotop/7z-tools)
  - Steg using 7zip
- [BinWalk]()
  - Looks through files for hidden files within
- [Sonic Visualizer](https://www.sonicvisualiser.org/)
  - For looking at audio files (especially in the spectogram)

### Password Cracking
- [CUPP](https://github.com/Mebus/cupp)
  - Useful for making password lists
- [jtr](https://github.com/openwall/john)
  - Password cracking tool
- [SecLists](https://github.com/danielmiessler/SecLists)
  - Password lists


### Miscellanous
- [ROT8000](https://rot8000.com/Index)
  - Rotates Unicode characters by 0x8000. Mostly chinese characters.
- [AndroidBackuptoolkit]()
  - used when messing with android backups

## Python Libraries

### Stego 
- [Wave](https://docs.python.org/3/library/wave.html)
  - Used for messing with audio files
- [Pillow](https://pillow.readthedocs.io/en/stable/)
  - For messing with images in python
