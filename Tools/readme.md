# Tools List: Readme


♥ Add descriptions/links to your favorite ctf tools, scripts & repos here! ♥
(If this list gets too big it can be split up into separate folders.)
Add custom scripts in their own subfolder if needed.

---
## Image Recovery/Manipulation/Stegonography

Tools for graphical images (jpg/png/gif etc) - recovering, repairing, manipulating, carving, deobfuscating, stego, etc.
Useful reference for CTFs involving image format flags.

### PCRT (PNG Check & Repair Tool)
https://github.com/sherlly/PCRT
Python script for quick-and-dirty PNG repair.
* Repairs corruption: PNG header error, wrong IHDR chunk crc due to error picture's width or height, wrong IDAT chunk data length due to DOS->UNIX conversion, wrong IDAT chunk crc due to its own error, lost IEND chunk
* Extracts data after IEND chunk (Malware programs like use this way to hide)
* Shows the repaired image
* Injects payload into image
* Decompresses image data and shows the raw image

### Testdisk & Photorec
https://www.cgsecurity.org/wiki/TestDisk
Testdisk reads/repairs corrupt partitions. Photorec does blind/FS-less file carving. Photorec in particular is ideal for trawling through an image looking for anything photo-like in raw storage (without regard to filesystem) :)

### Stegsolve
https://github.com/zardus/ctf-tools/blob/master/stegsolve/install

---
## Cryptography

Tools for encrypting, decrypting, analysing etc

### Feather Duster
https://github.com/nccgroup/featherduster
Cryptoanalysis and breaker tool for identifying and exploiting weak cryptosystems. 

### Decode.fr
https://dcode.fr
(Translated to English: https://translate.google.com.au/translate?sl=auto&tl=en&u=https%3A%2F%2Fwww.dcode.fr)
Website providing multiple decryption/puzzle solving tools. Decryption, frequency analysis, cipher decoding, etc.

---
## Digital Forensics

Tools for data acquisition, data validation, log capture/analysis, FS examination etc


---
## Credentials enumeration & password cracking

Tools for enumerating users, guessing/bruteforcing passwords, reversing hashes, useful wordlists & rainbow tables, etc


---
## Domain/Directory Enumeration

Tools for enumerating (sub)domains & directories 


---
## Shells

Tools for getting & escalating shells


---
 ♥ ♥ ♥ ↑↑↑ Please keep adding more in - tools you already use, plus anything new you use/find along the way! ↑↑↑ ♥ ♥ ♥
