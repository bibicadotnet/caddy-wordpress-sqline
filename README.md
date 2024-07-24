# Caddy Wordpress Sqline

 ................


### Installation
1. Clone repo
```
git clone https://github.com/bibicadotnet/caddy-wordpress-sqline
```
2. Change SERVER_NAME 
```
caddy-wordpress-sqline/config/.env
```
3. Run docker
```
cd caddy-wordpress-sqline/
docker-compose pull && docker-compose up -d
```
4. Setup Wordpress Sqline
```
sudo wget https://raw.githubusercontent.com/bibicadotnet/caddy-wordpress-sqline/main/setup_wordpress.sh -O setup_wordpress.sh && sudo chmod +x setup_wordpress.sh && sudo ./setup_wordpress.sh
```
