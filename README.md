# @hoc-element/affix

![npm](https://img.shields.io/npm/v/@hoc-element/affix)  ![NPM](https://img.shields.io/npm/l/@hoc-element/affix)

📌 将页面元素固定在可视范围内。

**Live demo:** https://pdsuwwz.github.io/hoc-element-affix

## Environment Support

* Vue 2.5.17

## Install

```shell
npm install @hoc-element/affix
```

## Quick Start

```js
import Vue from 'vue'
import HocElementAffix from '@hoc-element/affix'

Vue.use(HocElementAffix)
```

## Using

可选参数

| 字段 | 说明 | 类型 | 默认值 |
| -------- | -------- | -------- | -------- |
| offsetTop | 距离窗口顶部多少时开始固定 | Number | 0 |

## Demo

```html
<template>
  <hoc-el-affix
    :offsetTop="10"
  >
    <div class="demo"></div>
  </hoc-el-affix>
</template>
<style lang="scss" scoped>
  .demo {
    position: absolute;
    width: 150px;
    height: 300px;
    border: 1px solid red;
  }
</style>

```

