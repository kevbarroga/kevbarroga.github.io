---
layout: post
title: "Install Telegram messaging desktop app"
date: 2017-08-09
---

1. Download [Telegram Desktop](https://telegram.org/dl/desktop/linux) app for Linux
2. Move to download location. `cd ~/Downloads`
3. Extract *tar* file `tar -xJvf tsetup.X.X.X.tar.xz`
4. Move extracted *Telegram* folder to */opt/telegram* directory  `sudo mv Telegram /opt/telegram`
5. Create soft link of Telegram app */opt/telegram/Telegram* to */usr/bin/telegram* `sudo ln -sf /opt/telegram/Telegram /usr/bin/telegram`
6. Start *Telegram* `./Telegram`
