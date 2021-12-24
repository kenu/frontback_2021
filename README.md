# frontback
* This project is for SPA app with API backend development environment.

## Development
### Backend
```
git clone https://github.com/kenu/frontback.git
cd frontback/backend
npm install
npm run dev
open http://localhost:4000
```

### Frontend
```
cd frontback/frontend
npm install
npm run dev
open http://localhost:3000
```

## Production
### Backend
```
npm i -g pm2
git clone https://github.com/kenu/frontback.git
cd frontback/backend
npm install
pm2 start bin/www --name web
```

### Frontend
```
cd frontback/frontend
npm install
npm run build
cp -r dist/* ../backend/public
```

## Swagger
* http://localhost:4000/api-docs
