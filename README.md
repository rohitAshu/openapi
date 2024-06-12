# openapi

DeFi wallet on Chia Network.

## Install

You can install Goby [here](https://chrome.google.com/webstore/detail/goby/jnkelfanjkeadonecabehalmbgpfodjm).

## Run your own node

```
git clone https://github.com/GobyWallet/openapi.git
cp settings.toml.default settings.toml
# change settings.toml
pip install -r requirements.txt

# start api
uvicorn openapi.api:app

# start watcher 
python -m openapi.watcher
```


