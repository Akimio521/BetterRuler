# JoinUs
**欢迎加入我们！**

## 步骤
1. Fork本项目到自己的仓库中
2. Clone到本地
3. 增加内容
4. 推送到自己的仓库中
5. 提交PR

## 注意事项
1. 记得添加Script脚本到本仓库中，插件&复写中要指向本仓库的文件
2. 记得修改README，记录添加/修改时间
3. 如果插件有图标，将图标添加到仓库的ICON目录下
4. 记得使用CDN链接，方便在无代理的情况下更新插件/复写
5. 复写/插件请用官方指定后缀
6. 不予以合并乱写的Commit

## 目前已知可用的Github国内CDN
1. **jsDelivr**（推荐）：`https://cdn.jsdelivr.net/gh/用户名/仓库@分支/文件名`
2. **Github Proxy**：在Github原链接前面加入`https://ghproxy.com/`

## 官方后缀说明
- QuantumultX：snippet
- Loon：plugin
- Surge：sgmodule
- Stash：stoverride
- Shadowrocket：sgmodule

## 关于命名规范
- 西文：同一单词首字母大写，例如：BoxJS.js、SubStore.plugin
- 中文：若有西文名，优先使用网址/应用的西文名，若无西文名，则采用拼音，例如：钱迹APP -> QianJi
- 日文：若有西文名，优先使用网址/应用的西文名，若无西文名，则采用罗马音

## 关于图标
- 如果作者原本提供了图标，将图片放入ICON目录下
- 若使用的是APP插件，建议通过[HQ-ICON](https://github.com/YuKongA/HQ-ICON)获取AppStore图标
    - 网址：https://icon.yukonga.top/
    - 原始图像
    - png格式
    - 108px
    - 放入仓库ICON/APP目录下，要符合命名规范

## 关于分类
原则是按照APP在APPstore中的类别进行分类，若是非APP相关应用，则默认是`其他`