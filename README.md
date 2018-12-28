"# octobercms-docker" 
## 1. CREATE YAML FILE "docker-compose.yml"
## 2. ssh to container 
docker exec -it < container name > /bin/bash 
## 3. Go to html folder were the site should reside
## 4. Update composer
composer update
## 5. install october with composer https://octobercms.com/docs/console/commands#console-install
composer create-project october/october .
## 6. Install with artisan october db
php artisan october:install
## 7. DONE - GO TO http://localhost/
## 8. Check OctoberCMS admin
	http://localhost/backend 
	user: admin 
	pass: admin


