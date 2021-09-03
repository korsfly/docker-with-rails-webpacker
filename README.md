1. `docker-compose build`

2. `docker-compose run --rm app bundle exec rails webpacker:install`

3. `docker-compose run --rm app rails db:create && db:migrate`

3. `docker-compose up`
