# tbot
- install penunjang
- sudo apt install jq
- wget -L https://raw.githubusercontent.com/selerakucs1/tbot/main/start.sh
- nano start.sh
- chmod +x start.sh
- /start.sh
- sudo crontab -e */60 * * * * bash /root/start.sh > /root/start.log 2>&1
