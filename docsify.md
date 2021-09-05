#### [docsify官网地址](https://docsify.js.org/#/zh-cn/)

#### 快速开始
```
// 全局安装，Mac需要sudo
npm i docsify-cli -g
// 初始化
docsify init ./docs(文件夹名称)
// 预览
docsify serve ./docs
``` 

#### 相关配置
```
// index.html
window.$docsify = {
    name: '',
    repo: '',
    // 定制侧边栏
    loadSidebar: true,
    // 显示目录
    subMaxLevel: 2,
    // 自动为页面生成标题
    autoHeader: true,
    // 搜索
    search: 'auto',
}
```