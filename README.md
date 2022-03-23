# install penunjang
- sudo apt install jq
# copy start.sh & go
- wget -L https://raw.githubusercontent.com/selerakucs1/tbot/main/start.sh
- chmod +x start.sh
- ./start.sh
# optional one hour
- sudo crontab -e */60 * * * * bash/root/start.sh > /root/start.log 2>&1
