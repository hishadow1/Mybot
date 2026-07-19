sudo cp vps-bot.service /etc/systemd/system/vps-bot.service
sudo systemctl daemon-reload
sudo systemctl enable vps-bot.service
sudo systemctl start vps-bot.service
