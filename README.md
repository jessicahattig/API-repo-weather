# _APIs & Asynchrony_

#### By _**Jessica Hattig, Gareth Grindeland & Eusebie Siebenberg**_

####  _Application built to practice API calls using the OpenWeather API_

## Technologies Used

* Git
* HTML
* CSS
* JavaScript
* NodeJS version 16.13.1
* webpack version 4.46.0
* npm version 8.1.2
* Bootstrap version 5.2.3
* Postman

## Description

_Practice lesson to learn about APIs using OpenWeather API, Postman_

## Setup/Installation Requirements

* _Clone this repository to your desktop._
* _If you are creating a new repository, make sure the first file you add and commit is the .gitignore file._
* _Navigate to the top level of the directory._
* _Update the "name" key in the package.json file to the name of the new project_
* _If there are other source files to add (CSS, JS, and HTML), make sure to import them to the index.js entry point file._
* _To generate a new package.json file, run this in the command line:_
```
$ npm init -y
```
* _Run the following code to install packages:_
```
$ npm install
<!--if you run into errors, delete node_modules file and rerun the install command-->
$ npm run build     <!--tell webpack to build the bundle-->
$ npm run start     <!--build the project and serve it with a web server-->
```
* _After completing this setup, we're ready to write code in the src folder._
* _If you add other dependencies, make sure to update the 'devDependencies' and 'scripts' sections within the 'package.json' file._
* _To install other specific package versions, use the code:_

```
$ npm install [PACKAGE-NAME]
<!--for example:-->
$ npm install webpack@4.46.0 --save-dev 
$ npm install webpack-cli@3.3.12 --save-dev
$ npm install jest@24.9.0 --save-dev
$ npm install @babel/core@7.18.6 --save-dev
$ npm install @babel/plugin-transform-modules-commonjs@7.18.6 --save-dev
$ npm install file-loader --save-dev
$ npm install html-loader@1.3.2 --save-dev
```

* _List of useful npm script terminal commands:_
```
$ npm install
$ npm uninstall
$ npm init -y
$ npm run build
$ npm run start
$ npm run lint
$ npm run test
```


## Known Bugs

* _No known bugs_

## License

## [MIT](https://opensource.org/license/mit/)

Copyright (c) 2023 Jessica Hattig, Gareth Grindeland, Eusebie Siebenberg

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

If you have any questions, comments, or concerns, please reach out to us at siebenee@gmail.com