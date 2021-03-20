![](https://cdn.jsdelivr.net/gh/wangxingkang/pictures@latest/imgs/picture.png)

现在已有很多收费的图床服务，基于能白嫖就白嫖的原则，利用免费的资源，制作一个免费图床。

本文涉及的软件和网站主要包括 [PicGo](https://picgo.github.io/PicGo-Doc/zh/)、[Github](https://github.com) 、[jsdelivr](https://www.jsdelivr.com/) :

- PicGo  支持多个图床的图床工具
- Github 图片存储地址
- jsdelivr 免费的CDN服务

## 一、图片存储

本图床使用Github作为免费的图片资源存储地址，下面介绍具体的步骤。

### 1. 新建一个项目

![](https://cdn.jsdelivr.net/gh/wangxingkang/pictures@latest/imgs/20210318233955.png)

按照上图所示，输入仓库名称，点击创建按钮，即可完成图床仓库的创建。

## 创建Github访问令牌

![](https://cdn.jsdelivr.net/gh/wangxingkang/pictures@latest/imgs/20210318234246.png)

操作路径: 点击头像 >> Settings >> Developer settings >> Personal access tokens

如上图所示，填写完成后点击下方的创建按钮，完成后拷贝生成的访问令牌，将在设置PicGo时使用。

## 二、设置PicGo

### 1. 下载安装PicGo

请安照官网进行[安装](https://picgo.github.io/PicGo-Doc/zh/guide/#%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85)，这里不再累述。

### 2. 设置PicGo

![](https://cdn.jsdelivr.net/gh/wangxingkang/pictures@latest/imgs/20210320084131.png)

自定义域名请设置为  `https://cdn.jsdelivr.net/gh/{Github 用户名}/{仓库名称}@latest/` 

token设置为上文github生成的访问令牌





