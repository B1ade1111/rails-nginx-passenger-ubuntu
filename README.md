add nginx to service
```
git clone https://github.com/B1ade1994/rails-nginx-passenger-ubuntu
sudo cp rails-nginx-passenger-ubuntu/nginx/nginx /etc/init.d/
sudo chmod +x /etc/init.d/nginx
rm -rf rails-nginx-passenger-ubuntu
sudo service nginx start
```
OR
```
sudo wget -O init-deb.sh https://www.linode.com/docs/assets/660-init-deb.sh
sudo mv init-deb.sh /etc/init.d/nginx
sudo chmod +x /etc/init.d/nginx
sudo /usr/sbin/update-rc.d -f nginx defaults
```
