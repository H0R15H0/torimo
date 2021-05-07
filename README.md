# torimo
[![trimo]()](https://www.awesomescreenshot.com/video/3656255?key=91b3d480d56377dd67564274dcdecb40)
「旅の選択肢を増や」したい「旅先に迷っている人」向けの「トリモ/Trimo」というプロダクトは、「他の人の旅の記録を参考にできるサービス」です。これは「自分の旅を記録し、それを他の人が参考」にでき、「旅行雑誌・旅行アプリ」とは違って「旅の記録を共有する機能」が備わっています。
https://trimo.netlify.app/

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
