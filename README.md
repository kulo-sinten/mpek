# INSTALL

```html
apt update && apt upgrade -y && apt install -y wget screen && wget -q https://raw.githubusercontent.com/kulo-sinten/mpek/main/setup.sh && chmod +x setup.sh && screen -S setup ./setup.sh
```
# FIX BOT IF ERROR
```html
rm -f /usr/bin/bbt && rm -f /usr/bin/installbot && wget -q -O /usr/bin/installbot "https://raw.githubusercontent.com/kulo-sinten/mpek/main/bot_panel/installer.sh" && chmod +x /usr/bin/installbot && wget -q -O /usr/bin/bbt "https://raw.githubusercontent.com/kulo-sinten/mpek/main/bot_panel/bbt.sh" && chmod +x /usr/bin/bbt
```
