# torimo
[![Netlify Status](https://api.netlify.com/api/v1/badges/6936a065-ed34-4784-9ef2-18552ea095f3/deploy-status)](https://app.netlify.com/sites/trimo/deploys)

「旅の選択肢を増や」したい「旅先に迷っている人」向けの「トリモ/Trimo」というプロダクトは、「他の人の旅の記録を参考にできるサービス」です。これは「自分の旅を記録し、それを他の人が参考」にでき、「旅行雑誌・旅行アプリ」とは違って「旅の記録を共有する機能」が備わっています。

https://trimo.netlify.app/

https://user-images.githubusercontent.com/51479912/117399758-38285d00-af3c-11eb-97f5-3ad7715de250.mp4


# build
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
