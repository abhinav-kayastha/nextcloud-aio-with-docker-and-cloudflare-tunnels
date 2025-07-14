🐳 Nextcloud AIO Docker Setup

Create a folder:

    mkdir nextcloud-aio && cd nextcloud-aio

Copy docker-compose.yml into the folder.

Launch Nextcloud:

    docker-compose up -d

Access locally at: http://localhost:11000

🌐 Cloudflare Tunnel Setup

Install cloudflared and login:

    sudo apt install cloudflared

    cloudflared tunnel login

Create tunnel:
    
    cloudflared tunnel create nextcloud

  Use the cloudflared-config.yml and place it at:

    ~/.cloudflared/config.yml
