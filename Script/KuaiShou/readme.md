###  获取Cookie方法
  1. 点击视频页悬浮红包，或者进入设置，点击"积分兑好礼"即可

 >>> [回到顶部](#IOS配置教程)

### Nodejs 配置密钥 (Github Actions)

<details>

  <summary>
    <span style="font-size:22">
       Actions Secrets 
    </span>
  </summary>  

| Name | 脚本相关YML | Value分割符 | 必须 / 可选 | 注意事项及样式(其中"xxx"代表任意字符) |
| :-------: | :------: | :-------: | ------ | ------- |
| KS_TOKEN | <span style="font-size:18; color:#0000ff"> 快手视频 </span> | &或换行 | 必须 | 请求地址: "https://activity.m.kuaishou.com/rest/wd/taskCenter/lowActive/module/list"， <br>任务Cookie: uid=xxx&gsid=xxx&s=xxx |

</details>

 >>> [回到上一页](..)
 
### 注意事项:
 * 本脚本仅限快手视频"低活国庆"部分任务，不能自动刷视频，可以自动领取视频积分
 * 本脚本仅适用于快手双版本签到，仅支持正式版获取多Cookie，建议使用正式版获取Cookie
