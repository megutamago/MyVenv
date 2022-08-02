# MyVenv

windows terminal json
```
    "defaultProfile": "{2c4de342-38b7-51cf-b940-2309a097f518}",
    "initialCols": 100,
    "initialRows": 30,
    "profiles": 
    {
        "defaults": {},
        "list": 
        [
            {
                "backgroundImage": "C:\\hoge\\hoge13.jpg",
                "backgroundImageOpacity": 0.29999999999999999,
                "font": 
                {
                    "face": "Monofur Nerd Font",
                    "size": 10
                },
                "guid": "{2c4de342-38b7-51cf-b940-2309a097f518}",
                "hidden": false,
                "name": "Ubuntu",
                "source": "Windows.Terminal.Wsl"
            },
```

python venv create
```
sudo apt install -y python3-venv
cd ~ && \
mkdir venvs && \
cd venvs && \
python3 -m venv venv && \
. venv/bin/activate
```

terraform install
```
wget -O- https://apt.releases.hashicorp.com/gpg | gpg --dearmor | sudo tee /usr/share/keyrings/hashicorp-archive-keyring.gpg
echo "deb [signed-by=/usr/share/keyrings/hashicorp-archive-keyring.gpg] https://apt.releases.hashicorp.com $(lsb_release -cs) main" | sudo tee /etc/apt/sources.list.d/hashicorp.list
sudo apt update && sudo apt install terraform
```


