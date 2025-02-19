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

{% note blue 'fas fa-gift' modern %}
**▌ MTR HostingProject 永久免费托管**  
✓ 零成本运营：月访问量≥100 PV自动续期  
✓ 开发环境自由选：  
  - PHP/Go项目（**限量开放**）  
  - Node.js/Python/静态网站（**无限量申请**）
{% endnote %}

{% note purple 'fas fa-users' flat %}
**▌ 用户特权说明**  
{% label 1级用户 red %}（默认）：  
› 无限创建静态网站  
› 自助管理基础配置  

{% label 2级用户 green %}（东方众专享）：  
› 解锁PHP/Go项目优先资格（{% label 1级用户 red %} 也可申请）  
› 获取建站操作指导  
› 技术问题优先响应
{% endnote %}

{% note green 'fas fa-link' modern %}
**▌ 免费域名方案**  
① `*.free.mtr.pub`：  
   - 三级域名，即时开通  
② `*.kmtr.work`：  
   - 二级域名，需说明用途  
③ `*.youmu.ltd`：  
   - 二级域名，需达成进阶条件
{% endnote %}

{% note red 'fas fa-exclamation-circle' simple %}
**▌ 重要须知**  
• 技术支持：**空闲时段提供基础帮助，不承诺解决 ** 
• 服务条款：不提供SLA，无法保证99%在线率，但是会尽力保障正常运行
• 禁止行为：**挖矿/攻击/违规内容将永久封禁**
{% endnote %}

{% note orange 'fas fa-heart' disabled %}
**▌ 支持我们**  
维护服务器需要咖啡续命 ☕  
扫码捐助请备注联系方式：  
![二维码](https://img.youmu.ltd/file/AgACAgUAAyEGAASSRK4yAAMLZ7XXxuD14LygW91VaMdHLqBczgUAAmbDMRuhhqhVHMa_WPhpZDcBAAMCAAN3AAM2BA.png)
{% endnote %}