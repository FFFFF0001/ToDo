
## ToDo

最近做事情总是丢三落四，老忘记一些重要的事情，就突发奇想写了这个 `ToDo` 待办事宜的app。

1. [项目地址](https://htmlpreview.github.io/?https://github.com/zc95/ToDo/blob/master/index.html#)
2. [github地址](https://github.com/zc95/ToDo)

<p style="text-align:center;">
<img style="box-shadow:1px 1px 10px #888888;"  src="https://ws1.sinaimg.cn/large/006tNc79gy1fn87kbo8mmj30xr1o014t.jpg" width="90%;">
</p>


<!-- more -->

## 主要功能

1. 可以添加待办事项到首页中，数据都是保存在本地localStorage的，只要不是手动删除或者换了设备，数据是永久保存的
2. 点击事项可以将待办事项的状态改为 `选中` 和 `未选中` ，每次改变状态都会保存到localStorage，每天的开始都可以点 `重置所有状态` 的按钮来设置所有的待办事项为未选中
3. 可以删除已添加的待办事项或者彻底删除所有本地localStorage数据



## 本地存储localStorage

```javascript
[{
  "text": "待办事项1",
  "id": "3e54ca37-ca25-4cf8-a5a8-f92a2137dd0d",
  "checked": "0"
},
{
  "text": "待办2",
  "id": "77b5044f-c352-e028-e2eb-8706fb27be2c",
  "checked": "0"
},
{
  "text": "哈哈哈哈",
  "id": "282ca71e-ae17-afc2-9d49-0c6d30c676fa",
  "checked": "0"
}]
```



