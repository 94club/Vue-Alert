# Vue-Alert
使用Vue.extend 扩展组件，以函数形式应用组件，自带确认/取消后的回调。

## 使用说明

- Vue 版本 2.4.2

- 安装方法 npm install Vue-Alert

```
  import Vue-Alert from 'Vue-Alert'

  Vue.prototype.$alert = Vue-Alert

  组件内使用： this.$alert(options)

  options : {
    title: '提示',  // 弹出框标题名称
    message: '',  // 弹出框提示信息
    onConfirm: false,  // 确认回调 非必须
    onCancle: false  // 取消回到 必须
  }

```
