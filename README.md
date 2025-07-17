# 一、项目介绍
采用**uniapp**开发,在线阅读系统管理员端,支持添加、修改、删除图书、添加、修改、删除广告,用户权限管理,数据仪表盘
## 1  服务端
[https://gitee.com/Qianrenni/online-reading-system](https://gitee.com/Qianrenni/online-reading-system)

## 2 客户端
[https://gitee.com/Qianrenni/online-reading-system-user](https://gitee.com/Qianrenni/online-reading-system-user)
# 二、项目结构
```bash 
├── .gitignore # git忽略文件
├── App.vue # 项目入口文件
├── common/ # 公共文件
|   ├── checker.js # 路由检查
|   └── qiun.css # 图形库全局样式
├── components/ # 组件
|   ├── advertisement-admin/ # 广告管理
|   |   └── advertisement-admin.vue 
|   ├── bookAdmin/ # 图书管理
|   |   └── bookAdmin.vue 
|   ├── BookUpload/ # 图书上传
|   |   └── BookUpload.vue 
|   ├── dashboard/ # 仪表盘
|   |   └── dashboard.vue
|   ├── mosowe-editor/ # 富文本编辑器
|   |   ├── mosowe-editor.vue
|   |   └── readme.md
|   ├── person_admin/ # 用户管理
|   |   └── person_admin.vue
|   ├── u-charts/ # 图表
|   |   ├── u-charts.js
|   |   ├── u-charts.min.js
|   |   └── u-charts.vue
├── configJs/ # 配置
|   └── protectedRoutes.js # 路由保护
├── index.html #入口html
├── main.js #入口js
├── manifest.json  # manifest
├── package.json # package
├── pages/ # 页面
|   ├── admin/ # 管理员
|   |   └── admin.vue
|   ├── login/ # 登录
|   |   └── login.vue
|   ├── previewAndEdit/ # 书籍预览编辑
|   |   └── previewAndEdit.vue
├── pages.json # 页面配置
├── README.md # 项目说明
├── static/ # 静态资源
|   ├── customicons.css
|   ├── customicons.ttf
|   ├── image/
|   |   └── index.png
├── store/ # 状态管理
|   ├── index.js
├── uni.scss # 全局样式
└── utils/ # 工具类
|   ├── cache.js # 缓存
|   └── router.js #路由保护
```

# 三、联系作者
邮箱：<2112183503@qq.com>


