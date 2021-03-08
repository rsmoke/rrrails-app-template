# README
## This template has Rails / ActiveAdmin / Devise

Static pages for
- Aboout
- Privacy
- Terms of use
## Useful bits
- ```git clone <repo>```
- ```cd <app directory>```
- ```docker-compose run --rm web bundle```
- edit database.yml to reflect name of your application
- ```docker-compose run --rm web rails db:create```
- ```docker-compose run --rm web rails db:migrate```
- ```docker-compose run --rm web rails db:seed```
- ```docker-compose run --rm web yarn```
- ```docker-compose up```

look for your application in a browser: localhost:3001

- run the following command if see errors in localhost:30001
- ```docker-compose run --rm web yarn upgrade```

#### If you add anything to the app you will need to run ??????
```
docker-compose up --build
````
### If your app is ugly run
```docker-compose run --rm web yarn```
- then call Rita B for help
