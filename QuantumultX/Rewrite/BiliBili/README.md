# 哔哩万象BiliUniverse
## 安装
### 重写
- [Enhanced-QuantumultX重写](https://cdn.jsdelivr.net/gh/Akimio521/BetterRuler@main/QuantumultX/Rewrite/BiliBili/BiliBili.Enhanced.snippet)
- [ADBlock-QuantumultX重写](https://cdn.jsdelivr.net/gh/Akimio521/BetterRuler@main/QuantumultX/Rewrite/BiliBili/BiliBili.ADBlock.snippet)
- [BoxJS订阅](https://cdn.jsdelivr.net/gh/Akimio521/BetterRuler@main/BoxJS/BiliUniverse.json)

## Enhanced
### 简介
- 支持粉/白版本
- 保持模块开启，即可全面自定义哔哩哔哩app主界面
- 版本不同，功能会有些许差异

### 功能列表
- 首页页面
    - 标签页: 自定义启用的首页标签页，建议不超过7个
    - 默认 标签页: 选择启动APP时默认展示的标签页
        - 需选择已启用的标签页,否则默认为第一个标签页
    - 顶栏左侧按钮（用户头像）: 选择该按钮的作用
        - BiliBili粉色版无法修改
    - 顶栏右侧按钮: 选择启用的按钮
- 底部导航栏
    - 自定义启用的底部导航栏，最多6个
- 我的页面
    - 自定义启用的我的菜单选项
- 分类页面
    - 自定义启用的分类菜单选项

## Global
⚠️Bilibili app所使用的gRPC接口已移除HTTP/1.1兼容性，仅保留HTTP/2协议支持
因为QuantumultX不支持MitM over HTTP/2
此模块已不再支持QuantumultX

## ADBlock
### 简介
- 保持模块开启，即可去除哔哩哔哩app内广告元素
- 注：
    - 版本不同，功能会有些许差异

### 功能列表
- 自定义开启`推荐及广告`菜单选项