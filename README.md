# TikTok
IOS
TikTok在IOS端免拔卡使用条件：<br>
1:美区ID<br>
[TikTok小火箭专用免费ID](https://bgpnet.org/auth/register?code=bPpx)
2:下载小火箭<br>

3：配置小火箭<br>

4：采用Fiddle+i4Tools爱思工具+Ituns+美区AppleID, 下载旧版本的TikTok（21.1.0）安装<br>

Shadowrocket配置文件代码：
```bash
[URL Rewrite]
(?<=_region=)CN(?=&) JP 307
(?<=&mcc_mnc=)4 2 307
^(https?:\/\/(tnc|dm)[\w-]+\.\w+\.com\/.+)(\?)(.+) $1$3 302
(^https?:\/\/*\.\w{4}okv.com\/.+&.+)(\d{2}\.3\.\d)(.+) $118.0$3 302

[MITM]
hostname = *.tiktokv.com,*.byteoversea.com,*.tik-tokapi.com
```
注：国家JP可更改对应地区简写，如美区简写US

[Dolphinanty  TikTok免费专版指纹浏览器下载](https://bit.ly/3wMXt3q)


Fiddle使用方法：
1：安装
2：Tools→Options→Https→Decrypt Https traffic→Check for Certificate revocation → Actions→Trust Root Certificat→Yes →是 →是 →确定→ OK

COPY Fiddle Code: 
```bash
bpu MZBuy.woa
```

TikTok版本ID：
```bash
844024073、843972181
```
