# 超叫兽 · chaojiaoshou

内容出海专家 · 助力中国创作者的内容出海

[访问 chaojiaoshou.com](https://chaojiaoshou.com/)

首页是一张单屏名片。桌面横向排列个人简介和场记板人像，手机上使用竖版照片。简介下方展示六个内容平台的单色图标，访客可以扫描微信二维码添加好友。

## 版本记录

[v1.0.1](https://github.com/superchaospc/chaojiaoshou/releases/tag/v1.0.1) 更新了主页简介和网页描述，浏览器标签页也换上了超叫兽的个人头像。

## 本地预览

在仓库根目录运行以下命令，然后打开 [本地预览](http://localhost:8000/)。

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

## 更新主页

| 要修改的内容 | 对应文件 |
| --- | --- |
| 姓名、简介、社媒图标和分享信息 | [index.html](index.html) |
| 字体、配色、二维码尺寸和手机布局 | [style.css](style.css) |
| 桌面和手机人像 | [横版照片](assets/slate-landscape.jpg)、[竖版照片](assets/slate-portrait.jpg) |
| 微信联系方式 | [二维码](assets/wechat-qr.svg) |
| 浏览器标签页图标 | [favicon.ico](favicon.ico) |

替换二维码后，可从桌面和手机预览各截一张图，用微信识别，确认打开的是正确的联系人。

## 部署

GitHub Pages 从 `main` 分支的根目录发布静态文件。将修改推送至 `main` 后，可以在 [Actions](https://github.com/superchaospc/chaojiaoshou/actions) 查看部署进度。[CNAME](CNAME) 指定自定义域名，网站已启用 HTTPS。
