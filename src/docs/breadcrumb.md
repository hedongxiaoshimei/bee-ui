## breadcrumb 面包屑

### 基本用法 （依赖vue-router）

::: demo 
``` html
<template>
  <bee-bread-crumb :crumbs='crumbs'></bee-bread-crumb>
</template>

<script>
export default {
  data () {
    return {
      crumbs: [{
        label: '首页',
        route: {
          path: '/'
        }
      }, {
        label: '安装',
        route: '/components/install'
      }, {
        label: '面包屑',
        route: ''
      }]
    }
  }
}
</script>
```
:::


### 属性值

|参数|说明|类型|可选值|默认值|
|---|---|---|---|---|
|crumbs|数据源|array|—|-|