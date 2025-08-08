

</div>
<p align="center">
  <img src="https://i.imgur.com/LyHic3i.gif" />
</p>

<p align="center">
  <img src="https://i.pinimg.com/736x/f5/f7/4a/f5f74ae26480cd5b2635ed6a824f27bd.jpg" />
</p>

<!-- 📊 STATS & HERO ANIMATION (Updated Colors) -->
<div align="center">


# TEST-MD Setup


###  Step 1: Get Your Session ID

Authenticate using **one** of the methods below to generate your `Session ID`.

<p align="center">
  <img src="https://i.imgur.com/LyHic3i.gif" alt="Authentication Flow Preview" />
</p>

>  Pair Code Authentication

[![Get Pairing Code](https://img.shields.io/badge/Get%20Pairing%20Code-orange?style=for-the-badge&logo=opencv&logoColor=black)](https://malvinxd-pairsession.onrender.com/pair)

>  QR Code Authentication

[![Scan QR Code](https://img.shields.io/badge/Scan%20QR%20Code-000000?style=for-the-badge&logo=react&logoColor=white)](https://malvinxd-pairsession.onrender.com/qr)


<p align="center">
  <img src="https://i.imgur.com/LyHic3i.gif" alt="Authentication Flow Preview" />
</p>




<p align="center">
  <img src="https://i.imgur.com/LyHic3i.gif" width="65%" />
</p>

<p align="center" style="color:#777;font-size:13px;">
  <img src="https://github.com/XdKing2/MALVIN-XD/blob/main/assets/warning.gif?raw=true" width="15" />
  <em>Having connection issues? Try using a VPN.</em>
</p>



<br>
<a><img src='https://i.imgur.com/LyHic3i.gif'/>

 <h4 align="center">9. Workflow</h4>
<p style="text-align: center; font-size: 1.2em;">


<details>

<b><strong><summary align="center" style="color: Yello;">Deploy Malvin On Workflow</summary></strong></b>
<p style="text-align: center; font-size: 1.2em;">
 
<h8>Copy the workflow codes and then fork the repo edit config add session id then save and now click on repo action tag then click on start new workflow then paste workflow codes rename main.yml to deploy.yml and save the file</h8>
<h3 align-"center"> Important</h3>
<h6 align-"center">Attention! We do not take responsibility if your github account is suspended through this Deploy method, I advise you not to use this workflow deploy method in the latest github accounts, github accounts created a year or more ago have not received the risk of suspension so far, this works It will only be done for 6 hours, you need to update the code to reactivate it.</h6>

```
name: Node.js CI

on:
  push:
    branches:
      - main
  pull_request:
    branches:
      - main

jobs:
  build:

    runs-on: ubuntu-latest

    strategy:
      matrix:
        node-version: [20.x]

    steps:
    - name: Checkout repository
      uses: actions/checkout@v3

    - name: Set up Node.js
      uses: actions/setup-node@v3
      with:
        node-version: ${{ matrix.node-version }}

    - name: Install dependencies
      run: npm install

    - name: Start application
      run: npm start
```
</details> 

  <img src="https://i.imgur.com/LyHic3i.gif" width="100%" />
</p>


powerd by TEST-MD
