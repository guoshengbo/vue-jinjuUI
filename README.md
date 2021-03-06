# vue-flip-number

基于 Vue 2.x 的数字切换组件

![screenshot](https://github.com/guoshengbo/vue-flip-number/blob/master/png.jpg?raw=true)

## 安装

```
npm i vue-flip-number --save
```

## 使用

```vue
<template>
  <div>
    <flip :deadline="deadline" :length="length"></flip>
  </div>
</template>

<script>
  import Flip from 'vue-flip-number'

  export default {
      data () {
        deadline: 999999,
        length: 10
      }
      components: { Flip }
  }
</script>
```
deadline（number）:需显示的数字        

length（number）：一共显示多少位（不能小于deadline长度，多出部分填充0显示）
# 参考

- [vuejs-countdown](https://github.com/getanwar/vuejs-countdown)
- [Demo for 'Flip clock & countdown, Vue'](https://codepen.io/shshaw/pen/BzObXp)
