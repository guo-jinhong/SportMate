运动搭子/
├── app.js          // 全局入口（全局变量、生命周期）
├── app.json        // 全局配置（页面路由、导航栏样式）
├── app.wxss        // 全局样式（统一字体、颜色、间距）
├── pages/          // 核心页面（按功能模块划分）
│   ├── home/       // 首页·地图
│   │   ├── home.wxml  // 页面结构
│   │   ├── home.wxss  // 页面样式
│   │   ├── home.js    // 页面逻辑（定位、地图互动）
│   │   └── home.json  // 页面配置（导航栏标题）
│   ├── dynamic/    // 动态模块
│   │   ├── dynamic.wxml
│   │   ├── dynamic.wxss
│   │   ├── dynamic.js
│   │   └── dynamic.json
│   ├── publishDynamic/  // 发布动态（单独页面，简化操作）
│   │   ├── publishDynamic.wxml
│   │   ├── publishDynamic.wxss
│   │   ├── publishDynamic.js
│   │   └── publishDynamic.json
│   ├── sport/      // 运动模块（打卡、轨迹）
│   │   ├── sport.wxml
│   │   ├── sport.wxss
│   │   ├── sport.js
│   │   └── sport.json
│   ├── activity/   // 活动模块
│   │   ├── activity.wxml
│   │   ├── activity.wxss
│   │   ├── activity.js
│   │   └── activity.json
│   └── mine/       // 我的模块（主页、设置）
│       ├── mine.wxml
│       ├── mine.wxss
│       ├── mine.js
│       └── mine.json
├── components/     // 公共组件（复用性强，减少重复代码）
│   ├── mapAvatar/  // 地图头像组件（好友/附近用户）
│   ├── activityCard/  // 活动卡片组件（首页/活动页复用）
│   ├── dynamicItem/    // 动态列表项组件（动态页复用）
│   └── publishBtn/     // 发布按钮（全局复用，固定在底部）
├── utils/          // 工具函数（复用逻辑，简化页面代码）
│   ├── http.js     // 网络请求封装（对接后端接口）
│   ├── location.js // 定位工具（处理定位权限、自由选点）
│   └── format.js   // 格式处理（时间、距离格式化）
└── images/         // 静态资源（图标、默认图片，统一管理）
    ├── icon/       // 功能图标（定位、匹配、发布）
    └── default/    // 默认图片（默认头像、空状态图）