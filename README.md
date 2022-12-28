# Wa-OpenAI

***WhatsApp OpenAI Create with NodeJS Using Library [Baileys](https://github.com/adiwajshing/Baileys)***
## BACA DULU
Terdapat 2 tipe yaitu menggunakan command dan tanpa menggunakan command (auto chat).
- Jika ingin menggunakan command silahkan ganti kata ```true``` menjadi ```false``` di file [key.json](https://github.com/dappaqt/wa-openAI)<br>Untuk commandnya menggunakan ```.ai```
- Jika tidak ingin menggunakan command (auto chat) silahkan ganti kata ```false``` menjadi ```true``` di file [key.json](https://github.com/dappaqt/wa-openAI/blob/main/key.json#L3)

## Get & Change OpenAI ApiKey
- Jika limit ApiKey OpenAI sudah habis silahkan buat apikey yang barunya [Disini](https://beta.openai.com/account/api-keys)
- Ganti ApiKey OpenAI pada file [key.json](https://github.com/dappaqt/wa-openAI/blob/main/key.json#L2)

## Install
**Install on RDP/Windows ✅**

Install [NodeJS](https://nodejs.org/en/download/)
 dan [Git Bash](https://git-scm.com/downloads) terlebih dahulu
```bash
$ git clone https://github.com/dappaqt/wa-openAI
$ cd Wa-OpenAI
$ npm install
$ node index.js
```
**Install on Termux ✅**

Silahkan install manual ```node_modules``` terlebih dahulu, karena di termux saat install otomatis melalui ```npm install``` terjadi error.
<br>Link ```node_modules```: [Klik Disini](https://drive.google.com/file/d/1gKGjseRirX6mQ5LOFULpmnDs7q3Svm8y/view?usp=sharing)
```bash
$ pkg install git nodejs -y
$ git clone https://github.com/dappaqt/wa-openAI
$ cd Wa-OpenAI
```
Sesusah menginstall file node_modules, silahkan extract file ```node_modules.zip``` dan taruh di folder Wa-OpenAI.

**Run**
```bash
$ node index.js
```

## License
[MIT License](https://github.com/dappaqt/wa-openAI/blob/main/LICENSE.md)

Copyright (c) 2022 M Yusril

