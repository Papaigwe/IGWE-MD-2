## 🌟 `Bot Intro and Features`
</div>
  <a href="https://sessi-id-by-igwe-tech.onrender.com/">
        <p align="center">
   <img alt="papaigwe" height="300" src="https://i.imgur.com/zWW3hlV.jpeg">
              </p>
  </a>
</p>
   
<p align="center">

  <a aria-label="Join our chats" href="https://whatsapp.com/channel/0029Vak1chV4Y9lkl89DuD3j" target="_blank">
    <img alt="whatsapp" src="https://img.shields.io/badge/Join Group-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" />
  </a>

  
<p align="center">

  <a aria-label="Tutorial" href="https://whatsapp.com/channel/0029Vak1chV4Y9lkl89DuD3j" target="_blank">
    <img alt="youtube" src="https://img.shields.io/badge/tutorial-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" />
  
<div align="center">

**IGWE-MD-2 is a multi-device bot that can help you with different things on WhatsApp developed by [IGWE THE KING](https://github.com/papaigwe)**

</div>

### FORK THIS REPO

1. Must Fork This Repo Before Deployment !
   <br> 
<a href="https://github.com/Papaigwe/IGWE-MD-2/fork"><img title="FORK REPO" src="https://img.shields.io/badge/FORK REPO-h?color=black&style=for-the-badge&logo=stackshare"></a>



### SESSION ID

2. Upload the creds.json that you received to the session folder.
   <br>
<a href='https://sessi-id-by-igwe-tech.onrender.com/' target="_blank"><img alt='PAIR CODE' src='https://img.shields.io/badge/session_id-100000?style=for-the-badge&logo=scan&logoColor=white&labelColor=black&color=black'/></a>

### DEPLOY TO WORKFLOWS

#

<details close>
<summary>CLICK</summary>

**Create a new file [`.github/workflows/deploye.yml`] After created, copy this code👇🏽and paste it there.**
```yml
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

#### DEPLOY TO HEROKU 

1. If You don't have a account in Heroku. Create a account.
    <br>
<a href='https://heroku.com' target="_blank"><img alt='Replit' src='https://img.shields.io/badge/-Create-black?style=for-the-badge&logo=heroku'/></a>
   <br>
2. Now Deploy
    <br>
<a href='https://dashboard.heroku.com/new?button-url=https%3A%2F%2Fgithub.com%2Ftoge012345%2FTOGE-V3-AI%3Ftab%3Dreadme-ov-file&template=https%3A%2F%2Fgithub.com%2Fpapaigwe%2FIGWE-MD-2%3Ftab%3Dreadme-ov-file' target="_blank"><img alt='DEPLOY' src='https://img.shields.io/badge/-DEPLOY-black?style=for-the-badge&logo=heroku'/></a>

#### DEPLOY ON RAILWAY

1. If You don't have a account in Railway. Create a account.
    <br>
<a href='https://railway.app' target="_blank"><img alt='Replit' src='https://img.shields.io/badge/-Create-black?style=for-the-badge&logo=railway'/>
2. Now Deploy
    <br>
<a href='https://railway.app' target="_blank"><img alt='DEPLOY' src='https://img.shields.io/badge/-DEPLOY-black?style=for-the-badge&logo=railway'/></a>


#### DEPLOY ON MOGENIUS

1. If You don't have a account in Replit. Create a account.
    <br>
<a href='https://mogenius.com' target="_blank"><img alt='Replit' src='https://img.shields.io/badge/-Create-black?style=for-the-badge&logo=genius'/></a>
2. Now Deploy
    <br>
<a href='https://mogenius.com' target="_blank"><img alt='DEPLOY' src='https://img.shields.io/badge/-DEPLOY-black?style=for-the-badge&logo=genius'/></a>

#### DEPLOY TO REPLIT 

1. If You don't have a account in Replit. Create a account.
    <br>
<a href='https://www.replit.com/' target="_blank"><img alt='Replit' src='https://img.shields.io/badge/-Create-black?style=for-the-badge&logo=replit'/></a>
   <br>
2. Now Deploy
    <br>
<a href='https://replit.com/github/toge012345/IGWE-MD-2' target="_blank"><img alt='DEPLOY' src='https://img.shields.io/badge/-IMPORT-black?style=for-the-badge&logo=replit'/></a>
##
### Termux/Ssh/Ubuntu

<details>
  <summary>Please click here for more assist.</summary>
    
   ### `🌟 There are two common ways to deploy on Termux/Ssh/Ubuntu.`
   ***- Using clone method from github repository.***
   ```
apt update
apt upgrade
pkg update && pkg upgrade
pkg install bash
pkg install libwebp
pkg install git -y
pkg install nodejs -y 
pkg install ffmpeg -y 
pkg install wget
pkg install imagemagick -y
npm install ytdl-core@latest
git clone https://github.com/papaigwe/IGWE-MD-2
cd IGWE-MD-2
yarn install
npm start
```

  ### ***`Second Method:`***
  ***- Using download method to local storage.***
  
  Step: 1
    ***Download [`IGWE-MD-2`](https://github.com/papaigwe/IGWE-MD-2/archive/refs/heads/Master.zip) repository first.***

  Step: 2
    ***Extract the downloaded `.zip` file.***

  Step: 3
    ***Edit `lib/database/owner.json` file (enter ownernumber).***
    
  Step: 4
    ***Go to your `termux/Ssh/Ubuntu` terminal and navigate to your folder path.***
  ***- For Example:***
  
  ```
  cd /sdcard/download/IGWE-MD-2
  ```

  Step: 5
    ***Enter the followings commands in your `terminal`.***

 ```
apt update
apt upgrade
pkg update && pkg upgrade
pkg install bash
pkg install libwebp
pkg install git -y
pkg install nodejs -y 
pkg install ffmpeg -y 
pkg install wget
pkg install imagemagick -y
npm install ytdl-core@latest
```

  Step: 6
    ***`Install dependencies:`***

```
yarn install
```

  Step: 7
    ***`Run your bot:`***

```
npm i -g pm2 && pm2 start index.js && pm2 save && pm2 logs
```


 ## `Main Dev` 
<a href="https://github.com/papaigwe"><img src="https://i.imgur.com/onulEbP.jpeg" width="250" height="250" alt="PAPA IGWE"/></a>
  
`IGWE TECH INC.`

##
- This bot is not made by `WhatsApp Inc.` So misusing the bot might `ban` your `WhatsApp account!`(Though your WhatsApp account can be unbanned only once.)
- I am not responsible for banning your account.
- Use at your own risk by keeping this warning in mind.


<h2 align="center">  NOTICE
</h2>
   
##
- Not For Sale
- If A plugin's code is obfuscated , You don't have permission to edit it in any form 
- Don't Forget to Give Credits If you are using or Reuploading My Plugins/files
- Have A Good Day Ahead

## THANKS USING IGWE-MD-2
<img alt="Development" width="250" src="https://media2.giphy.com/media/W9tBvzTXkQopi/giphy.gif?cid=6c09b952xu6syi1fyqfyc04wcfk0qvqe8fd7sop136zxfjyn&ep=v1_internal_gif_by_id&rid=giphy.gif&ct=g" /> </p>


