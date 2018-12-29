"# octobercms-docker" 
## 1. CREATE YAML FILE "docker-compose.yml"
## 2. ssh to container 
docker exec -it < container name > bash 
## 3. Go to html folder were the site should reside
## 4. Update composer
composer update
## 5. October migration
php artisan october:up
## 6. Update October
php artisan october:update
## 7. DONE - GO TO http://localhost/
## 8. Done - GO TO OctoberCMS admin
	http://localhost/backend 
	user: admin 
	pass: admin


