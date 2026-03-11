# 🦖 Google Dino Bot — The OG Youtube Dark Automation Hack
A fast, lightweight Dino Bot used back in the day to power YouTube Dark, YouTube Automation, and even Infinite Live loops.

<p align="center">
<img src="https://raw.githubusercontent.com/tuliosousapro/Google-Dino-Bot/d7dd083a5630216ade70d50d76a9576bbc08f2e6/0311.gif" alt="Dino Bot Demo" width="600">
</p>

<p align="center">
<a href="https://github.com/tuliosousapro/Google-Dino-Bot/stargazers"><img src="https://img.shields.io/github/stars/tuliosousapro/Google-Dino-Bot?style=flat&color=yellow"></a>
<a href="https://github.com/tuliosousapro/Google-Dino-Bot/issues"><img src="https://img.shields.io/github/issues/tuliosousapro/Google-Dino-Bot"></a>
<img src="https://img.shields.io/badge/Chrome-Dino%20Game-black">
<img src="https://img.shields.io/badge/Automation-Bot-blue">
</p>

### ⚡ What This Bot Does
- Automates the Chrome Dino game
- Works on [chromedino.com](https://chromedino.com) even when Chrome blocks scripts
- YouTube Bot to keep infinite livestreams alive
- No complex setup needed

Originally used to keep YouTube bots, automation channels, and infinite livestreams running without stopping

### 🚀 Quick Start
- Type `chrome://dino` into your Chrome browser address bar and press Enter.
- Open console (Ctrl+Shift+J)
- Paste the script from this repo
```bash
function keyDown(e){Podium={};var n=document.createEvent("KeyboardEvent");Object.defineProperty(n,"keyCode",{get:function(){return this.keyCodeVal}}),n.initKeyboardEvent?n.initKeyboardEvent("keydown",!0,!0,document.defaultView,e,e,"","",!1,""):n.initKeyEvent("keydown",!0,!0,document.defaultView,!1,!1,!1,!1,e,0),n.keyCodeVal=e,document.body.dispatchEvent(n)}function keyUp(e){Podium={};var n=document.createEvent("KeyboardEvent");Object.defineProperty(n,"keyCode",{get:function(){return this.keyCodeVal}}),n.initKeyboardEvent?n.initKeyboardEvent("keyup",!0,!0,document.defaultView,e,e,"","",!1,""):n.initKeyEvent("keyup",!0,!0,document.defaultView,!1,!1,!1,!1,e,0),n.keyCodeVal=e,document.body.dispatchEvent(n)}setInterval(function(){Runner.instance_.horizon.obstacles.length>0&&(Runner.instance_.horizon.obstacles[0].xPos<25*Runner.instance_.currentSpeed-Runner.instance_.horizon.obstacles[0].width/2&&Runner.instance_.horizon.obstacles[0].yPos>75&&(keyUp(40),keyDown(38)),Runner.instance_.horizon.obstacles[0].xPos<30*Runner.instance_.currentSpeed-Runner.instance_.horizon.obstacles[0].width/2&&Runner.instance_.horizon.obstacles[0].yPos<=75&&keyDown(40))},5);
```

> Nowadays, there are some trouble on using this script in Chrome, but you can still use it on [chromedino.com](https://chromedino.com)

Dino runs forever. Perfect for automation experiments (And Infinite Livestreams)

### 🔥 Zero dependencies
- Runs directly in the browser
- Perfect for YouTube Automation, Infinite Live, and Dark YouTube strategies
- Fun, fast, and hackable

### ⭐ Support
Star the repo to push it higher in GitHub search and help more automation creators find it.

> Back in the days I used this to make Youtube infinite lives.
