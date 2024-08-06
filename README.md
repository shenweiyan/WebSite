# WebSiteSRC - Website Source Code

沈维燕/章鱼猫先生/史提芬先森（Steven Shum）的个人博客源码。


### 安装部署

下载更新，更新子模块。

```
$ git clone https://github.com/shenweiyan/WebSiteSRC.git
$ cd WebSiteSRC
$ git submodule update --init --recursive
$ cd themes/ICS-Hugo-Theme
$ git pull https://github.com/shenweiyan/ICS-Hugo-Theme.git
```

### 发布站点

通过 GitHub Actions - [HugoAction.yml](https://github.com/shenweiyan/WebSiteSRC/blob/main/.github/workflows/HugoAction.yml)，本源码执行自动构建，并发布到以下仓库。

- GitHub: [ShumLab/ShumLab.github.io](https://github.com/ShumLab/ShumLab.github.io) (main)：
  - 启用 GitHub Pages，绑定以下域名：[https://www.shumlab.com/](https://www.shumlab.com/)

- GitHub: [shenweiyan/WebSite](https://github.com/shenweiyan/WebSite) (main)：
  - 启用 GitHub Pages，绑定以下域名：[https://shen.bioitee.com/](https://shen.bioitee.com/)
  - 启用 CloudFlare Pages，绑定自定义域名：[https://blog.weiyan.cc/](https://blog.weiyan.cc/)
