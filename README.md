# Nesa-Miner by @siavash3441

![Nesa Bootstrap Process](https://raw.githubusercontent.com/nesaorg/bootstrap/master/images/bootstrap.gif)
---
- Official Docs - https://docs.nesa.ai/nesa/run-a-nesa-node/prerequisites
- First get [whitelisted](https://beta.nesa.ai/) , if you are not whitelisted contact discord admin @fielding in miner channel to get whitelisted
 
Use these commands one by one
```bash
sudo apt update && sudo apt upgrade -y
```
```bash
sudo apt-get update
sudo apt-get install ca-certificates curl
sudo install -m 0755 -d /etc/apt/keyrings
sudo curl -fsSL https://download.docker.com/linux/ubuntu/gpg -o /etc/apt/keyrings/docker.asc
sudo chmod a+r /etc/apt/keyrings/docker.asc

echo \
  "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.asc] https://download.docker.com/linux/ubuntu \
  $(. /etc/os-release && echo "$VERSION_CODENAME") stable" | \
  sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
sudo apt-get update
```
```bash
sudo apt-get install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin
```
```bash
sudo groupadd docker
sudo usermod -aG docker $USER
```
- Command to check if jq is installed, If jq is not installed, the script will attempt to install it
```bash
jq --version
```

## Account and Token Requirements

### Hugging Face API Token

- You will need a Hugging Face API token, [HuggingFace](https://huggingface.co/docs/hub/security-tokens)
![image](https://i.postimg.cc/Z0kCLNKR/nesa-fu.jpg)

## Installation
```bash
bash <(curl -s https://raw.githubusercontent.com/nesaorg/bootstrap/master/bootstrap.sh)
```
- MODEL_NAME=
"nlptown/bert-base-multilingual-uncased-sendtiment"
- Referral Code:
- nesa1jgaxcu8vhch64h30gsh3d77u6qscjeq8wj69p6

- Check docker container
```bash
docker ps
```

- To get peer_id run the script again and check the right corner of your screen
 ```bash
bash <(curl -s https://raw.githubusercontent.com/nesaorg/bootstrap/master/bootstrap.sh)
```

- Check Node status : https://node.nesa.ai/nodes/YOUR_PEER_ID

- Done !! Feel free to ask queries in twitter
- twitter x - (https://x.com/zhiwani)

