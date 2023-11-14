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
	docker exec line-cms-back-app bash -c "cd /var/www/line/cms && php artisan migrate"

migrate-down:
	docker exec line-cms-back-app bash -c "cd /var/www/line/cms && php artisan migrate:rollback"

shell:
	docker exec -it line-cms-back-app bash
