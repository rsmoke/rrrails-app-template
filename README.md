# README
## This template has Rails / ActiveAdmin / Devise

Static pages for
- About
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

Look for your application in a browser: localhost:3001

### If your app is ugly run
```docker-compose run --rm web yarn upgrade```

#### If you add anything to the app you will need to run
```docker-compose up --build```

### Initial Admin Creds (CHANGE THIS!!)
```UserID: admin@example.com PWD: password```
