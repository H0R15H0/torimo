# torimo
```
git clone git@github.com:H0R15H0/torimo-frontend.git frontend
git clone git@github.com:H0R15H0/rails-api.git api
docker-compose build
docker-compose run --rm frontend npm install
docker-compose run --rm api rails db:create
docker-compose run --rm api rails db:migrate
docker-compose up
```
