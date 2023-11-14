.PHONY: build sh run down

build:
	docker-compose build

up:
	docker-compose up

upd:
	docker-compose up -d

down:
	docker-compose down

migrate-up:
	docker exec line-api-app bash -c "cd /var/www/line/api && php artisan migrate"

migrate-down:
	docker exec line-api-app bash -c "cd /var/www/line/api && php artisan migrate:rollback"

shell:
	docker exec -it line-api-app bash
