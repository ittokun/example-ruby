db-setup:
	docker compose run --rm api rails db:create
	docker compose run --rm api rails db:migrate

db-access:
	docker compose exec db psql -U postgres postgres

api-bash:
	docker compose run --rm api bash

api-test:
	docker compose run --rm api rails test
