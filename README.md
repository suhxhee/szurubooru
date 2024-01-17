# szurubooru

Szurubooru 是一个图像板引擎，其灵感来自于 Danbooru、Gelbooru 和 Moebooru，致力于中小型社区。 

它的名字[源于波兰语，具有刮擦或擦洗的拟声含义](https://sjp.pwn.pl/sjp/;2527372)。

它的发音为 *shoorubooru*.

## 特点

- 帖子内容: 图片 (JPG, PNG, GIF, animated GIF), 视频 (MP4, WEBM), Flash 动画
- 使用 [yt-dlp](https://github.com/yt-dlp/yt-dlp 搜索网络视频内容
- 发表评论
-  笔记 / 注释, 包括任意的 polygons
- 丰富的 JSON REST API ([see documentation](doc/API.md))
- 基于 Token 的客户端身份验证
- 丰富的搜索系统
- 丰富的权限系统
- 搜索和编辑标签时自动补全
- 标签类别
- 标签建议
- 标签 implications（添加标签会自动添加另一个标签）
- 标签别名
- Pools 与 pool 分类
- 检测重复图片
- 评分和收藏; comment 评分
- 精美的用户界面
- 浏览器可配置无限分页
- 浏览器可配置透明图像的背景网格

## 安装

建议使用Docker进行部署。
[See installation instructions.](doc/INSTALL.md)

更多安装资源以及相关项目可以在
[GitHub project Wiki](https://github.com/rr-/szurubooru/wiki)

## 展示图

帖子列表：

![20160908_180032_fsk](https://cloud.githubusercontent.com/assets/1045476/18356730/3f1123d6-75ee-11e6-85dd-88a7615243a0.png)

帖子查看：

![20160908_180429_lmp](https://cloud.githubusercontent.com/assets/1045476/18356731/3f1566ee-75ee-11e6-9594-e86ca7347b0f.png)

## 许可证

[GPLv3](LICENSE.md).
