---
title: 目前为止的服务列表
date: 2025-02-15 17:42:59
tags: 闲谈
---

在这里记录一下目前为止的个人提供的服务。

{% note warning %}
本文档的时效性存疑。可能不会保持时时最新的状态。
{% endnote %}

- 名称：**GitHub Readme Stats**
- 说明：在你的 README 中获取动态生成的 GitHub 统计信息！
- 访问：{% btn 'https://grs.mtr.pub/',查看,fas fa-link,blue larger %}
- 备注：url：`https://grs.mtr.pub/`

-----
- 名称：**MTR Data**
- 说明：获取相关资源。
- 访问：{% btn 'https://dl.mtr.pub/zh-CN/',查看,fas fa-link,blue larger %}
- 备注：无
-----
- 名称：**神秘Reverser**
- 说明：可以实现一些神秘的目的。
- 访问：{% btn 'https://vcr.mtr.pub/',查看,fas fa-link,blue larger %}
- 备注：见下方代码块，能看懂的自用。
```json
{
  "rewrites": [
    { "source": "/proxy/:match/:url*", "destination": "https://:match/:url*" },
    { "source": "/proxy/:match/:url*/", "destination": "https://:match/:url*/" },
    { "source": "/httpproxy/:match/:url*", "destination": "http://:match/:url*" },
    { "source": "/httpproxy/:match/:url*/", "destination": "http://:match/:url*/" }
  ]
}
```
---
- 名称：**Meting API**
- 说明： 音乐解析API。
- 访问：{% btn 'https://meting.mtr.pub/',查看,fas fa-link,blue larger %}
- 备注： url： `https://meting.mtr.pub/`
---
- 名称：**Github镜像**
- 说明： 无。
- 访问：{% btn 'https://gh.youmu.ltd/',查看,fas fa-link,blue larger %}
- 备注： url： `https://gh.youmu.ltd/`
---
- 名称：**Github Gist镜像**
- 说明： 无。
- 访问：{% btn 'https://gist.youmu.ltd/',查看,fas fa-link,blue larger %}
- 备注： url： `https://gist.youmu.ltd/`
---
- 名称：**MTR Image**
- 说明： 提供免费的图床服务。
- 访问：{% btn 'https://img.youmu.ltd/',查看,fas fa-link,blue larger %}
- 备注： url： `https://img.youmu.ltd/`
---

{% note red 'fas fa-exclamation-circle' simple %}
**AD**  
**免费服务器** {% btn '/2025/02/22/costs/',点击链接查看,fas fa-link,blue larger %}
{% endnote %}