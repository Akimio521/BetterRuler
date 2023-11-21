# 哔哩万象BiliUniverse
## 安装
### 复写
- [Enhanced-Stash复写](https://cdn.jsdelivr.net/gh/Akimio521/BetterRuler@main/Stash/Override/BiliBili/BiliBili.Enhanced.sgmodule)
- [Global-Stash复写](https://cdn.jsdelivr.net/gh/Akimio521/BetterRuler@main/Stash/Override/BiliBili/BiliBili.Global.sgmodule)
- [ADBlock-Stash复写](https://cdn.jsdelivr.net/gh/Akimio521/BetterRuler@main/Stash/Override/BiliBili/BiliBili.ADBlock.sgmodule)
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
> ⚠️注意：使用前请务必检查`默认配置`是否与您的实际情况相符，如不符,请使用`BoxJs`正确填写要`启用的地区`和对应`策略组或节点`名称

### 简介
- 自动识别番剧影视内容地区限制并切换线路至对应地区
    - 点开任意地区限制的番剧或影视内容，直接播放，无需配置文件内置策略与规则组
    - 局域网环境下，多设备同时观看不同地区内容，互不影响
- 自定义搜索地区，快捷返回各区搜索结果

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

### 功能列表
- 强制返回的CDN主机名类型
    - IP: 返回远端DNS解析地址（强烈不推荐！严重影响域名分流规则与CDN重定向）
    - HTTP: 返回HTTP域名（推荐，免去重定向时MitM操作）
    - HTTPS: 返回HTTPS域名（重定向时需对指定域名启用MitM）
        - 此选项不限于媒体流的解析结果，搜索等其他返回的内容如图片音频也受此选项影响
        - 选择返回域名的情况下，对于本身无域名只有IP的返回结果无效
- 自动识别和分类功能地区设置
    - 务必与代理软件策略相对应
- 搜索时自定义搜索地区
    - 搜索关键词 + 空格 + 地区名称
    - 如：电锯人 🇭🇰 或 辉夜 台湾 或 尼尔 港
    - 支持的地区关键词有：
        - 中国大陆：CN CHN 中 中国 🇨🇳
        - 中国香港：HK HKG 港 香港 🇭🇰
        - 中国澳门：澳 澳门 🇲🇴
        - 中国台湾：TW TWN 台 台湾 🇹🇼
        - ~~东南亚（国际版）：SEA 东南亚 🇺🇳 TH 泰 泰国 🇹🇭 SG 新 新加坡 🇸🇬 MY 马 马来西亚 🇲🇾~~
        - ~~东南亚（国际版）未来可能细分~~
        - 国际版已拆分独立

## ADBlock
### 简介
- 保持模块开启，即可去除哔哩哔哩app内广告元素
- 注：
    - 版本不同，功能会有些许差异

### 功能列表
- 自定义开启`推荐及广告`菜单选项