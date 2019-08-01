#### GULP

### 範例測試
[How to use this](https://github.com/wagerfield/parallax) 

4. Development
4.1 Running the Project
- Clone the Repository git clone git@github.com:wagerfield/parallax.git
- Open the working directory cd parallax
- Install dependencies npm install
- Run development server gulp watch
- Open http://localhost:9000/ in browser


### 解決方法
- npm install
- npm install gulp-cli -g
- npm install gulp -D
- npx -p touch nodetouch gulpfile.js
- npm install gulp-sass
- gulp watch

> 產生錯誤
> 
<code>
    gulp task issue with nodejs v10.3.0 : src\node_contextify.cc:629: Assertion `args[1]->IsString()' failed
</code>

> 解決方法
[gulp watch失敗的問題](https://stackoverflow.com/questions/50620673/gulp-task-issue-with-nodejs-v10-3-0-src-node-contextify-cc629-assertion-arg) 
- delete node_modules directory 
- delete package-lock.json. Then run 
- npm install --unsafe-perm=true
- gulp watch
- working now~

