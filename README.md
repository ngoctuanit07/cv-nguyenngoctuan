# Deploy with Yarn
#### Start
`yarn start`
#### Deploy to github page
`yarn run deploy`


# Deploy with Docker (Not suggest)
```
docker-compose build
docker-compose up
```
Publish in http://localhost:3002

![](https://i.imgur.com/vBOkflC.gif)

***note: need config git with below option:
```
git config --global user.name "Tuan Nguyen"
git config --global user.email "tuannguyen0719@gmail.com"
```
### Deploy
```
docker-compose run mycv yarn run deploy
```
