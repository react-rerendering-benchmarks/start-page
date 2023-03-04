## Y-tab 轻起始页

### 扩展介绍
 - 基于React18、Antd5、valtio、TypeScript构建的一个简易起始页。
 - 启用后，此扩展会将空白页更改为起始页导航

### 兼容性
 - chrome浏览器
 - edge浏览器

### 初始化 & 启动
```pnpm install && pnpm dev```

### 编译

```pnpm build```

out_dir: start-page-dist

### 设置
 - 搜索设置
   - 是否在新标签页打开搜索结果
   - 是否在新标签页打开书签
   - 搜索结果是否屏蔽CSDN
 - 时间是否显示秒
 - 主题
    - 全局颜色修改
    - 背景图片修改（未开发完成）


### 更新
 - 0.0.1
   - 暂时隐藏背景图修改
   - 底部添加一言api
   - bugfix
 - 0.0.2
   - 新增屏蔽CSDN开关
   - 新增联想词搜索功能(可点击搜索，上下选中待定)
   - 增加了一些过渡动画，稍微丝滑了一点
   - bugfix
