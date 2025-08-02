# Building chains of double triple and more VPN + Cloudflare + Tor
https://youtu.be/KXM0GckmJAo

bash <(curl -Ls IP.Check.Place) -l en
sudo apt-get update && sudo apt-get upgrade -y
https://github.com/MHSanaei/3x-ui
bash <(curl -Ls https://raw.githubusercontent.com/mhsanaei/3x-ui/master/install.sh)

https://freedns.afraid.org/

wget -qO- speedtest.artydev.ru | bash

wget -qO- bench.sh | bash

https://pkg.cloudflareclient.com/#ubuntu
# Add cloudflare gpg key
curl -fsSL https://pkg.cloudflareclient.com/pubkey.gpg | sudo gpg --yes --dearmor --output /usr/share/keyrings/cloudflare-warp-archive-keyring.gpg

# Add this repo to your apt repositories
echo "deb [signed-by=/usr/share/keyrings/cloudflare-warp-archive-keyring.gpg] https://pkg.cloudflareclient.com/ $(lsb_release -cs) main" | sudo tee /etc/apt/sources.list.d/cloudflare-client.list

# Install
sudo apt-get update && sudo apt-get install cloudflare-warp

# Settings
warp-cli registration new
warp-cli mode proxy 
warp-cli connect

# Link to registration and 20% cashback discount on AEZA VPS registration💵 
https://aeza.net/?ref=554977
