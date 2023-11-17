# Spotify
## 歌词翻译
### 关于翻译接口
采用百度翻译接口进行翻译,需要先免费申请百度翻译api的id和密钥

> 标准版(很可能不够用):单次最长请求1000字符,免费调用量5万字符/月,QPS=1
> 高级版:单次最长请求6000字符,免费调用量100万字符/月,QPS=10

#### 申请步骤百度翻译接口
1. 注册百度翻译个人开发者: http://api.fanyi.baidu.com/register
2. 注册后如果需要认证可自行选择是否实人认证(高级版需要验证)
3. 开通(通用翻译)API服务: https://fanyi-api.baidu.com/choose
4. 成功后即可看到自己的appid和密钥(不要泄露给任何人): http://api.fanyi.baidu.com/manage/developer

### 启用翻译
修改配置文件，若之前以及使用Spotify会员解锁模块，则无需添加MITM
```config
[MITM]
hostname = %APPEND% spclient.wg.spotify.com
[Script]
# 修改下方argument中的appid和securityKey,填入自己的appid和密钥
spotify歌词翻译 = type=http-response,pattern=^https:\/\/spclient\.wg\.spotify\.com\/color-lyrics\/v2\/track\/,requires-body=1,binary-body-mode=1,max-size=0,script-path=https://cdn.jsdelivr.net/gh/Akimio521/BetterRuler@main/Script/Spotify/spotify-lyric.js,argument=appid=111&securityKey=xxx
```
