▄████████    ▄████████    ▄████████  Channel : @TTTZTTT \n  ███    ███   ███    ███   ███    ███   ███    ███ \n  ███    ███   ███    █▀    ███    █▀    ███    ███ \n  ███    ███  ▄███▄▄▄      ▄███▄▄▄      ▄███▄▄▄▄██▀  DEV : @TTTZTTT\n  ███    ███ ▀▀███▀▀▀     ▀▀███▀▀▀     ▀▀███▀▀▀▀▀   \n  ███    ███   ███    █▄    ███    █▄  ▀███████████ JOKER : @hi66x\n  ███    ███   ███    ███   ███    ███   ███    ███ \n   ▀██████▀    ██████████   ██████████   ███    ███ جاري تنصيب سورس جور\e[0m"
echo -n "جاري تحميل مكتبة python3.8.." 
sudo apt-get update -y &>/dev/null
sudo add-apt-repository ppa:deadsnakes/ppa -y &>/dev/null
sudo apt-get update -y &>/dev/null
sudo apt install python3.8 -y -y &>/dev/null
sudo apt install python3-pip -y &>/dev/null
sudo python3.8 -m pip install --upgrade pip &>/dev/null
echo -e "\rتم تحميل مكتبة  python3.8"
echo -n "تحميل باقي المكاتب.." 
sudo apt-get update -y &>/dev/null
sudo python3.8 -m pip install -U Pyrogram &>/dev/null
sudo python3.8 -m pip install -U tgcrypto &>/dev/null
sudo python3.8 -m pip install redis &>/dev/null
sudo apt-get install redis-server -y &>/dev/null
sudo systemctl enable redis-server.service -y &>/dev/null
echo -e "\rتم تحميل المكاتب المهمة"
echo -n "تحميل الاعدادات.."
sudo pip3 install requests &>/dev/null
echo -e "\rتم تحميل جميع المكاتب"
echo -n "جاري تحميل مكتبة pm2.." 
curl -sL https://deb.nodesource.com/setup_12.x | sudo bash - &>/dev/null; sudo apt-get update &>/dev/null; sudo apt install nodejs -y &>/dev/null; sudo npm install -g pm2 &>/dev/null
echo -e "\rتم تحميل مكتبة  pm2"
echo جاري تحميل سورس ر.." 
git clone https://github.com/BBTBB/JOKER1.git &>/dev/null
echo -e "\rتم تنصيب سورس كارلوس بنجاح"
