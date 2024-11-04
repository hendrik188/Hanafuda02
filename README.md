# Hanafuda
Automate grow for Hana Network Hanafuda campaign

# Registration
register on https://hanafuda.hana.network/ using google account

use code 
```
NEANZ3
```

Deposit First to obtain more grow attempt every hour.

# Installation
Install python and pip
```
sudo apt update && sudo apt install -y python3 python3-pip && python3 --version && pip3 --version
```
Install and make screen (so it can run on background)
```
sudo apt install screen
screen -S hanafuda
```
Git clone
```
git clone https://github.com/hendrik188/hanafuda.git
cd Hanafuda
```
Install dependencies
```
pip install -r requirements.txt
```
get API and Refresh token from inspect element

![image](https://github.com/user-attachments/assets/417911e0-dc0a-4b97-bc62-e74133905332)

create .env (nano .env) and fill with :
```
API_KEY=your_api_key_here (start with AIxxxxxxxxxx)
REFRESH_TOKEN=your_refresh_token_here (start with AMf-xxxx)

```
save .env (ctrl + x + y)

Run script
```
python3 hanagrow.py
```
Set grow amount and enjoy
Detach screen by pressing CTRL + A + D
