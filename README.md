# torimo
```
git clone https://github.com/H0R15H0/torimo.git
cd torimo
git clone https://github.com/H0R15H0/torimo-frontend.git frontend
git clone https://github.com/H0R15H0/torimo-api.git api
docker-compose build
docker-compose run --rm frontend npm install
docker-compose run --rm api rails db:create
docker-compose run --rm api rails db:migrate
docker-compose up
```
## frontend 
localhost:8080
## api
localhost:3000
