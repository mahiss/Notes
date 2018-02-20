# Notes

AngularJs4
---------------------------------------
npm install -g @angular/cli
ng -v


new project add code
ng new hello-world

cd hello-world

ng serve


Ng g component my-component

https://loiane.com/2017/08/how-to-add-bootstrap-to-an-angular-cli-project/

https://www.youtube.com/watch?time_continue=2&v=kFTmoLm9Jwg

https://coursetro.com/posts/code/63/Angular-4-Animation-Tutorial
https://codecraft.tv/courses/angular/forms/model-driven/

ReactJs
--------------------

npm install -g create-react-app
create-react-app my-app

cd my-app
npm start

https://www.youtube.com/watch?v=JPT3bFIwJYA&list=PL55RiY5tL51oyA8euSROLjMFZbXaV7skS&index=1
https://reactjs.org/tutorial/tutorial.html

npm init
npm install react react-dom --save
npm install webpack webpack-dev-server babel-loader babel-preset-es2017 babel-preset-react babel-preset-stage-2  --save-dev
npm start

package.json
"scripts": {
  "start": "npm run build",
  "build": "webpack -d && copy src\\index.html dist\\index.html && webpack-dev-server --content-base src --inline --hot",
  "build:prod": "webpack -p && copy src\\index.html dist\\index.html"
},

src/app/index.js
import React from "react";
import {render} from "react-dom";

class App extends React.Component {
    render() {
        return (
            <div className="container">
                <div className="row">
                    <div className="col-xs-10 col-xs-offser-1">
                        <h1>Hello!</h1>
                    </div>
                </div>
            </div>
        );
    }
}

render(<App/>, window.document.getElementById("app"));
src/index.html
<div id="app"></div>
router
npm install --save react-router
npm install react-router@3 --save
ID
npm install --save uuid

API
https://jsonplaceholder.typicode.com/
