---
layout: page
title: 觉得别人的域名很酷很有个性？你也可以！
categories:
     - 网站设计
---

##### 运用Gitee或GitHub可以部署属于自己的静态网页，那么怎么更改自己网站的域名呢？让自己的域名变得个性化？下面就来说下怎么在Gitee上更改自己部署的网站的域名。

- 首先，找到自己的仓库，点击右边的“管理”,在基本设置那，更改自己的**仓库名**和**路径**，更改成自己喜欢的名字。
- ![第一步](https://gitee.com/Xhewen/xiaohewen/raw/gh-pages/assets/images/%E7%BD%91%E7%AB%99%E8%AE%BE%E8%AE%A1%E6%96%87%E7%AB%A0-%E8%A7%89%E5%BE%97%E5%88%AB%E4%BA%BA%E7%9A%84%E5%9F%9F%E5%90%8D%E5%BE%88%E9%85%B7%E5%BE%88%E6%9C%89%E4%B8%AA%E6%80%A7%EF%BC%9F%E4%BD%A0%E4%B9%9F%E5%8F%AF%E4%BB%A5-%E6%AD%A5%E9%AA%A41.png)

- 接着，回到仓库，找到**_config.yml**文件 ，点进去。
- ![第一步](https://gitee.com/Xhewen/xiaohewen/raw/gh-pages/assets/images/%E7%BD%91%E7%AB%99%E8%AE%BE%E8%AE%A1%E6%96%87%E7%AB%A0-%E8%A7%89%E5%BE%97%E5%88%AB%E4%BA%BA%E7%9A%84%E5%9F%9F%E5%90%8D%E5%BE%88%E9%85%B7%E5%BE%88%E6%9C%89%E4%B8%AA%E6%80%A7%EF%BC%9F%E4%BD%A0%E4%B9%9F%E5%8F%AF%E4%BB%A5-%E6%AD%A5%E9%AA%A42.png)

- 最后在该文件里找到**baseurl**那行的代码，讲其改为你修改的仓库名即可。
- ![第一步](https://gitee.com/Xhewen/xiaohewen/raw/gh-pages/assets/images/%E7%BD%91%E7%AB%99%E8%AE%BE%E8%AE%A1%E6%96%87%E7%AB%A0-%E8%A7%89%E5%BE%97%E5%88%AB%E4%BA%BA%E7%9A%84%E5%9F%9F%E5%90%8D%E5%BE%88%E9%85%B7%E5%BE%88%E6%9C%89%E4%B8%AA%E6%80%A7%EF%BC%9F%E4%BD%A0%E4%B9%9F%E5%8F%AF%E4%BB%A5-%E6%AD%A5%E9%AA%A43.png)

- 这是以Jekyll静态网页为例更改域名的例子。

##### 希望大家都可以拥有一个自己喜欢的个性域名哟~