[简体中文](./README.md) | English

<div align='center'>

  <img src='https://github.com/PDKSophia/erek-resume-manage/raw/master/image/logo-1.png' width=340 height=220>

![](https://img.shields.io/badge/vue-2.5.2-blue.svg)
![](https://img.shields.io/badge/license-MIT-orange.svg)
![](https://img.shields.io/badge/echarts-4.1.0-yellow.svg)
![](https://img.shields.io/badge/iView-3.1.3-green.svg)
![](https://img.shields.io/badge/axios-0.18.0-red.svg)

</div>

# Vue-Erek-Manage

## Introduce

`Vue-Erek-Manage` is a backstage management system based on `Vue 2.0` and `iView UI`，It draws on `pro-ant-design` framework. 👉 It applies to background management for small projects

## Characteristic

- Configure `Menu bar` and `Breadcrumbs directly`
- Use `npm + webpack + babel` workflow , and support `ES6`
- Imitation `pro-ant-design` framework, provide `Echarts icon` and `Table form list` and other pages to learn from

## Technology

- vue-cli
- vuex
- axios
- vue-router
- scss
- iView
- echarts
- mock.js
- ...

## Target function

- [x] Dashboard
- [x] List Page
- [x] Error Page
- [x] Work Management
- [x] Person Page
- [x] Theme Setting

## Echarts

- [x] Line Echarts
- [x] Data Card
- [x] Pie Echarts
- [x] Radar Echarts
- [ ] ...(after doing QAQ)

## Project Environment

```javascript
    1 . Node.js is v10.6.0

    2 . Vue-cli is v3.0.0

    3 . Other dependencies please move package.json
```

## Use

```javascript
  1. git clone https://github.com/PDKSophia/vue-erek-manage

  2. cd vue-erek-manage

  3. npm install

  4. npm run serve
```

## Wiki Docs

> The use of the document is being written, please rest assured, as simple as possible, so that the big brothers are easy to get started, there is a saying that is good: **Refactoring is a daily thing, don't wait for the amount of code to come up, and cumbersome and then refactoring**

> please Don't leave me, I will speed up the progress, and if you think I am OK, give me a star ✨, it is an encouragement to me, love you.❤️

```
·
├── package.json
│ 
├── public
│ 
├── src
│   ├── assets
│   │
│   ├── components
│   │    ├─CommonComponents
│   │    │    ├─Badge
│   │    │    ├─Divider
│   │    │    ├─FolatButton
│   │    │    ├─NoContent
│   │    │    ├─StandCard
│   │    │    ├─StarCard
│   │    │    └─ ...
│   │    ├─EchartsCardComponents
│   │    ├─EchartsComponents
│   │    │    ├─Line
│   │    │    ├─Pie
│   │    │    ├─Radar
│   │    │    └─ ...
│   │    ├─FormComponents
│   │    │    ├─LoginForm
│   │    │    └─ ...
│   │    ├─FrameComponents
│   │    │    ├─Canvas
│   │    │    ├─Index
│   │    │    ├─Layout
│   │    │    ├─List
│   │    │    └─ ...
│   │    ├─HigherOrderComponents
│   │    │    ├─HOC-EchartCard
│   │    │    ├─HOC-EchartLine
│   │    │    ├─HOC-EchartPie
│   │    │    ├─HOC-EchartRadar
│   │    │    └─ ...
│   │    ├─ProfileTableComponents
│   │    │    ├─BaseTable
│   │    │    ├─AdvanceTable
│   │    │    └─ ...
│   │    └─ ...
│   │
│   ├── js
│   │    ├─app
│   │    │  ├─bread-config.js
│   │    │  ├─global-config.js
│   │    │  ├─index-config.js
│   │    │  ├─menu-config.js
│   │    │  └─ ...
│   │    ├─echarts
│   │    │    ├─line.config.js
│   │    │    ├─pie.config.js
│   │    │    ├─radar.config.js
│   │    │    └─ ...
│   │    ├─ mock
│   │    │    ├─app.js
│   │    │    ├─card.js
│   │    │    ├─data.js
│   │    │    ├─echarts.js
│   │    │    ├─list.js
│   │    │    ├─user.js
│   │    │    └─ ...
│   │    ├─utils
│   │    │    ├─utils.js
│   │    │    ├─vue-token.js
│   │    │    └─ ...
│   │    └─ ...
│   │
│   ├── router
│   │
│   ├── service
│   │    ├─api-app.js
│   │    ├─api-echarts.js
│   │    ├─api-list.js
│   │    ├─api-user.js
│   │    ├─index.js
│   │    ├─request.js
│   │    └─ ...
│   │
│   ├── store
│   │    ├─modules
│   │    │    ├─global.js
│   │    │    ├─standard.js
│   │    │    ├─table.js
│   │    │    ├─user.js
│   │    │    └─ ...
│   │    ├─index.js
│   │    ├─types.js
│   │    └─ ...
│   │
│   │
│   ├── view
│   │    ├─Index
│   │    ├─Login
│   │    ├─Manage
│   │    │    ├─VueErekException
│   │    │    ├─VueErekIndex
│   │    │    ├─VueErekList
│   │    │    ├─VueErekProfile
│   │    │    ├─VueErekTool
│   │    │    ├─VueErekUser
│   │    │    └─ ...
│   │    ├─Router.vue
│   │    └─ ...
│   │
│   ├── main.js
│   │
│   ├── App.vue
│   └─
│ 
├── vue.config.js
│ 
└─
```

## Display Picture

<img src='https://github.com/PDKSophia/erek-resume-manage/raw/master/image/ui-1.png'>

---

<img src='https://github.com/PDKSophia/erek-resume-manage/raw/master/image/ui-2.png'>

---

<img src='https://github.com/PDKSophia/erek-resume-manage/raw/master/image/ui-3.png'>

---

<img src='https://github.com/PDKSophia/erek-resume-manage/raw/master/image/ui-4.png'>

---

<img src='https://github.com/PDKSophia/erek-resume-manage/raw/master/image/ui-5.png'>

---

<img src='https://github.com/PDKSophia/erek-resume-manage/raw/master/image/ui-6.png'>

---

<img src='https://github.com/PDKSophia/erek-resume-manage/raw/master/image/ui-7.png'>

---

<img src='https://github.com/PDKSophia/erek-resume-manage/raw/master/image/ui-15.png'>

---

<img src='https://github.com/PDKSophia/erek-resume-manage/raw/master/image/ui-8.png'>

---

<img src='https://github.com/PDKSophia/erek-resume-manage/raw/master/image/ui-9.png'>

---

<img src='https://github.com/PDKSophia/erek-resume-manage/raw/master/image/ui-10.png'>

---

<img src='https://github.com/PDKSophia/erek-resume-manage/raw/master/image/ui-12.png'>

---

<img src='https://github.com/PDKSophia/erek-resume-manage/raw/master/image/ui-13.png'>

---

<img src='https://github.com/PDKSophia/erek-resume-manage/raw/master/image/ui-14.png'>

---

## Related links

blog: https://github.com/PDKSophia/blog.io

juejin: https://juejin.im/user/594ca8a35188250d892f4139

pro-ant-design: https://pro.ant.design/index-cn

---

Copyright © 2018 by PDK

If you have any questions, please contact me 1063137960@qq.com
