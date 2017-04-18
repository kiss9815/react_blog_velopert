"# react_blog_velopert"
velopert 블로그 따라한거
react_router 는 3. 버젼

-------------------------------------------------------------------------------------------



#스크립트

  "scripts": {
    "clean": "rm -rf build public/bundle.js",
    "build": "babel server --out-dir build && ./node_modules/.bin/webpack",
    "start": "NODE_ENV=production node ./build/main.js",
    "development": "NODE_ENV=development node ./build/main.js"
  },


#실행 방법
$ npm run build

$ npm run development
or
$ npm start
