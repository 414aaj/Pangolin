# Pangolin


<p align="center">
  <a href="https://github.com/414aaj/Pangolin/blob/main/README">English</a> •
  <a href="https://github.com/414aaj/Pangolin/blob/main/README_CN.md">中文</a> 
</p>

Disclaimer:

This tool is intended solely for network security research and educational purposes. It is designed to be used by skilled white-hat penetration testers for conducting legal penetration testing and security assessments. Unauthorized individuals should refrain from using or misusing this tool. Users must ensure the legality and compliance of their actions before using this tool. Any unauthorized network penetration, intrusion, or damage to others' networks is a violation of the law, and users are responsible for their actions. The developers and distributors of this tool do not bear any responsibility for any consequences arising from misuse or illegal use of the tool by users. Please adhere to local laws and regulations and obtain explicit authorization before using this tool for penetration testing or security research.

![P](https://github.com/user-attachments/assets/ff26ae80-8258-4a6d-8889-c446a12bc580)


The tool is developed using Go and Fyne, with built-in support for both Chinese and English languages. It currently focuses on proximity-based internal network penetration testing. At present, only the Android version is compiled (future versions for PC and iOS will be adapted and compiled as needed). It is clean and secure without any backdoors, and the program is not obfuscated, allowing for decompilation and inspection.

## Proxy
Supports HTTP and SOCKS5 global and local proxies (credential configuration not supported at the moment).


| <img src="https://github.com/user-attachments/assets/c8a89c8a-ba71-419d-80bd-33e8fbf90a26" width="400"/> | <img src="https://github.com/user-attachments/assets/84adb5d4-dd4c-4750-8e85-2a0ad3be5019" width="400"/> | <img src="https://github.com/user-attachments/assets/0fdbd392-abf3-44d3-9aa3-8ff8f5c51815" width="400"/> |
|:-----------------------------------------------------:|:-----------------------------------------------------:|:-----------------------------------------------------:|
| <img src="https://github.com/user-attachments/assets/d2222229-261e-4b6c-a620-385582a88705" width="400"/> | <img src="https://github.com/user-attachments/assets/f7f28d61-8e0d-465e-849d-939da802383e" width="400"/> | <img src="https://github.com/user-attachments/assets/fb89fe33-2052-4f29-82f7-82164cbe71bf" width="400"/> |



<img src="https://github.com/user-attachments/assets/dbc461e9-4068-4858-8619-9306362ff600"  width="50" height="50">


| <img src="https://github.com/user-attachments/assets/b7f65286-bdce-4c63-9deb-e16b1b75a79d" width="200"/> | <img src="https://github.com/user-attachments/assets/f6c641ab-998a-48f1-aa56-5cb8e71ae3de" width="200"/> |
|:-----------------------------------------------------:|:-----------------------------------------------------:|


## Host Alive Detection
Host alive detection uses the Ping command for probing (to avoid requiring root authorization).

## Port Scanning
Supports SOCKS5 proxy.
