# Useful tools:

## Virtual Machines

| Title | Reason | Link |
|-|-|-|
| Kali | Attack box for linux | [kali](https://kali.org)
| Flare | Malware Analysis tool for Windows | [flare](https://www.mandiant.com/resources/blog/flare-vm-the-windows-malware)
| Commando | Attack box based on Windows | [commando](https://www.mandiant.com/resources/blog/commando-vm-windows-offensive-distribution)

## Additional tools:
- [CyberChef](https://gchq.github.io/CyberChef/)
  - Very good for all sorts of stuff
- [NGROK](https://ngrok.com/)
  - Reverse proxy, to catch reverse shells or host websites to grab payloads off.

### Web
- [JWT](https://jwt.io/)
  - Decode Json Web tokens 

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
- [Wolfram Alpha](https://www.wolframalpha.com/)
  - Maths stuff but easier
-  [Dcode](https://www.dcode.fr/en)
  - All sorts of decoders 

### OSINT
- Oryon's OSINT Query Tool (Just google it.)
- [Sherlock](https://sherlock-project.github.io/)
  - Finds usernames of social media accounts.
- [What Three Words](https://what3words.com/)
  - Finds a place in the world based on three words.
 
### Stego
- [exiftool]()
  - view exif data of files
- [7ztools](https://github.com/yo-wotop/7z-tools)
  - Steg using 7zip
- [BinWalk]()
  - Looks through files for hidden files within
- [Sonic Visualizer](https://www.sonicvisualiser.org/)
  - For looking at audio files (especially in the spectogram)
- [zsteg]()
  - perl based tool to look at bmp and png steg
- [stegseek](https://github.com/RickdeJager/stegseek)
  - Like steghide but faster
- [MorseCode](https://morsecode.world/international/decoder/audio-decoder-adaptive.html)
  - Morse code from audio fast, from images/text use cyber chef  
- [DTMF Tones](http://dialabc.com/sound/detect/index.html)
  - Honestly IDK just plug in tones and it gives words 
- [Magic Eye](https://piellardj.github.io/stereogram-solver/)
  - Apparently you can be trained to read this but yeah for messy images
 
### Password Cracking
- [CUPP](https://github.com/Mebus/cupp)
  - Useful for making password lists
- [jtr](https://github.com/openwall/john)
  - Password cracking tool
- [SecLists](https://github.com/danielmiessler/SecLists)
  - Password lists

### PWN/Reveng
- [Ghidra](https://github.com/NationalSecurityAgency/ghidra/releases)
  - NSA uses this so must be good, static analysis
- [EDB Debug](https://github.com/eteran/edb-debugger)
  - Live debugging on linux
- [WinDBG](https://learn.microsoft.com/en-us/windows-hardware/drivers/debugger/debugger-download-tools)
  - Windows Debugging
- [ShellCode Debug](http://sandsprite.com/blogs/index.php?uid=7&pid=152)
  - For debugging windows shell code. cli

### Miscellanous
- [ROT8000](https://rot8000.com/Index)
  - Rotates Unicode characters by 0x8000. Mostly chinese characters.
- [AndroidBackuptoolkit](https://sourceforge.net/projects/android-backup-toolkit/)
  - used when messing with android backups

## Python Libraries

### Utility
- [UJSON](https://pypi.org/project/ujson/)
  - Like the json library but faster   
- [Sockets](https://docs.python.org/3/library/socket.html)
  - Messing around with sockets
- [Requests](https://requests.readthedocs.io/en/latest/)
  - Mess with web
- [BeautifulSoup4](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
  - HTML Parser used in conjunction with the previous tool    

### Stego 
- [Wave](https://docs.python.org/3/library/wave.html)
  - Used for messing with audio files
- [Pillow](https://pillow.readthedocs.io/en/stable/)
  - For messing with images in python

### Pwn/Reveng
- [PWNTools](https://docs.pwntools.com/en/stable/)
  - Collection of tools to help with pwn of binaries (Usually just use pwn)
