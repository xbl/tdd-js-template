# tdd-js-template


## 项目安装

项目需要 nodejs v8.0 及以上版本运行，添加了 [Babeljs](https://babeljs.io) ，所以可以使用 `class`、`arrow function`、`async` 等高级语法。测试使用了 [Mochajs](https://mochajs.org) 作为测试库，为不增加复杂性，使用 nodejs 自带的断言 [assert](https://nodejs.org/dist/latest-v10.x/docs/api/assert.html)，可根据开发者自己喜好更换。

进入目录后安装项目依赖：

```shell
npm install
# 或者
yarn
```

运行测试：

```shell
npm test
# 或者
yarn test

# watch 模式
npm run test
# 或者
yarn run test:watch
```

