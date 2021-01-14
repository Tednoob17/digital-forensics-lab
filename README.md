# Digital Forensics Lab

<img src="https://upload.wikimedia.org/wikipedia/commons/3/3c/BJA_Logo.png" width="150">

### Features of hands-on lab
===================
- Hands-on Digital Forensics Labs: Designed for Students and Faculty
- Each lab has a PPT with lab screenshots
- Purely based on Linux: Using Kali Linux
- Comprehansive: Cover many topics in digial forensics
- Free: All tools are open source
- Upated: The project is funded by DOJ and NSF and will keep updating 
---

## Table of Contents  (updating)
- Case Study
  * [Investigate NIST Data Leakage](#NIST-Data-Leakage)
  * [Investigate Illegel Possesion of Images](#Illegel-Possesion-of-Images)
  * [Investigate Email Harassment](#Email-Harassment)
- [Tools Used](#Tools-Used)


---
### NIST Data Leakage
==============

The  case study is to investigate an image involving intellectual property theft. The study include 

* A large and complex [image](https://www.cfreds.nist.gov/data_leakage_case/data-leakage-case.html) created by NIST
* 13 hands-on labs/topics in digital forensics


Topics Covered

| Labs | Topics Covered |Size of PPTs |
| --- | ----------- |----------- |
| Lab 0 | Environment Setting Up | 2M  |
| Lab 1 | Windows Registry  | 3M |
| Lab 2 | Windows Event and XML |3M |
| Lab 3 | Web History and SQL | 3M|
| Lab 4 | Email Investigation  |3M |
| Lab 5 | File Change History and USN Journal  |2M |
| Lab 6 | Network Evidence and shellbag |2M |
| Lab 7 | Network Drive and Windows shellbag |5M |
| Lab 8 | Master File Table ($MFT) Analysis |4M |
| Lab 9 | Windows Search History | 4M|
| Lab 10 | Windows Volume Shadow Copy Analysis |6M |
| Lab 11 | Data Carving |3M |
| Lab 12 | Crack Windows Passwords  | 2M|

---
### Illegel Possesion of Images
=====================

The case study is to investigate the illegel possession of Rhino images. This image was contributed by Dr. Golden G. Richard III, and was originally used in the DFRWS 2005 RODEO CHALLENGE. NIST hosts the [USB DD image](https://www.cfreds.nist.gov/dfrws/Rhino_Hunt.html). The copy of the image is also available in the repository.

Topics Covered

| Labs | Topics Covered |Size of PPTs |
| --- | ----------- |----------- |
| Lab 0 | HTTP Analysis using Wireshark (text)  | 3M  |
| Lab 1 | HTTP Analysis using Wireshark (image)  | 6M |
| Lab 2 | The Sleuth Kid Tutorial  | 1M |
| Lab 3 | Rhion Possesion Investigation 1: File recovering |9M |
| Lab 4 | Rhion Possesion Investigation 2: Steganography | 4M|
| Lab 5 | Rhion Possesion Investigation 3: Extract Evidence from FTP Traffic  |3M |
| Lab 6 | Rhion Possesion Investigation 3: Extract Evidence from HTTP Traffic  |5M |

### Email Harassment
=========

Topics Covered

| Labs | Topics Covered |Size of PPTs |
| --- | ----------- |----------- |
| Lab 0 | Investigating Harassment Email using Wireshark  | 3M  |
| Lab 1 | t-shark Forensic Introduction  | 2M |
| Lab 2 | Investigating Harassment Email using t-shark  | 2M |
---

---
### Tools Used
========
* Wine
* https://github.com/AtesComp/Vinetto
* https://github.com/Arthelon/imgclip
* Tree (apt-get install tree)
* https://github.com/keydet89/RegRipper3.0
* https://github.com/PoorBillionaire/Windows-Prefetch-Parser.git
* apt-get install python3-evtx
* apt-get install xmlstarlet
* apt-get install libhivex-bin
* apt-get install libesedb-utils 
* apt-get  install pasco
* https://github.com/libyal/libpff apt-get install pff-tools
* pip install usncarve
* pip install usnparser
* JLECmd wget https://f001.backblazeb2.com/file/EricZimmermanTools/JLECmd.zip
* apt-get install liblink-tuils
* https://github.com/digitalsleuth/time_decode
* pip install analyzeMFT
* https://github.com/libyal/libvshadow
* https://github.com/prolsen/recentfilecache-parser


## Contribution
=============
* Frank Xu
* Malcolm Hayward 
* Richard (Max) Wheeless
