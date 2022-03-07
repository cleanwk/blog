---
title: 每日一库&nodejs&chalk
date: 2022-03-07,13:03:1646631155
tags: [nodejs库]
---

## Chalk 是一个字符串着色库

#### 简单易用的api

```js
import chalk from 'chalk';

console.log(chalk.blue('Hello world!'));
```

#### 十六进制定制颜色

```
import chalk from 'chalk';

const error = chalk.bold.red;
const warning = chalk.hex('#FFA500'); // Orange color

console.log(error('Error!'));
```

#### 链式api

```js
console.log(chalk.red.bold.underline("str"))
```

