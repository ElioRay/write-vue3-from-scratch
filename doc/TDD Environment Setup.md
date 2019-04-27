## TDD Environment Setup

1. create repository

```sh
$ mkdir create-vue3-from-scratch
$ cd create-vue3-from-scratch
$ git init
```

2. [add .gitngnore](https://github.com/zzz945/write-vue3-from-scratch/commit/152224ee3fb730dad13b0cdfde37a7eee01abd7c#diff-a084b794bc0759e7a6b77810e01874f2)

3. init package.json

```sh
$ npm init
```

4. [install babel-loader](https://github.com/babel/babel-loader#install)

```sh
$ npm install -D babel-loader @babel/core @babel/preset-env webpack
```

6. [install karma](https://karma-runner.github.io/3.0/intro/installation.html)

```sh
# Install Karma:
$ npm install karma --save-dev

# Install plugins that your project needs:
$ npm install karma-jasmine karma-chrome-launcher jasmine-core --save-dev

$ npm install -g karma-cli
```

7. Init Karma
```sh
$ karma init # generate default config
```
 
7. [install](https://github.com/webpack-contrib/karma-webpack) and [config](https://github.com/zzz945/write-vue3-from-scratch/commit/9bf43f9b3ddc8f15a6b1d0e3ab77b725b339cb70#diff-a2a3b7b0c9c3b4b93b4aebf4e3ec3cfb) karma-webpack for test scripts to support es6

```sh
$ npm i -D karma-webpack
```

8. Write a [test case](https://github.com/zzz945/write-vue3-from-scratch/commit/9bf43f9b3ddc8f15a6b1d0e3ab77b725b339cb70#diff-4cec89e9e60decc25f7c64c8c8568760) to test ES6

```sh
$ karma start
```

HMR support. Test case will run on every save.