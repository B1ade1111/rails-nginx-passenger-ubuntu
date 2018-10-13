add nginx to service
```
git clone https://github.com/B1ade1994/rails-nginx-passenger-ubuntu
sudo cp rails-nginx-passenger-ubuntu/nginx/nginx /etc/init.d/
sudo chmod +x /etc/init.d/nginx
rm -rf rails-nginx-passenger-ubuntu
sudo service nginx start
```
