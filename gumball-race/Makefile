
# Compose

mysql-up:
	docker-compose up mysql -d

lb-up:
	docker-compose up -d lb

gumball-up:
	docker-compose up -d gumball

mysql-up:
	docker-compose up -d mysql

compose-up:
	docker-compose up --scale gumball=2 -d

compose-down:
	docker-compose down 	

lb-stats:
	echo "user = admin | password = admin"
	open http://localhost:1936

lb-test:
	open http://localhost




