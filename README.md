-------TBPL SERVER-------

RUN local server:
run 'yarn start'

HEROKU DEPLOY:
heroku create
git add .
git commit -m "sth"
git push heroku main /git push heroku HEAD:master

Vercel deploy:
add vercel.json
add "build": "node index.js" after scripts.start in package.json

run vercel
select the parameters it will create the api
