# resume-theme
this is a theme about resume based on hexo .

If you want to know how use the thme,please check on  [https://github.com/aeneag/resume-hexo](https://github.com/aeneag/resume-hexo)



Resume page [https://dxinxia.top](https://dxinxia.top)

Personal blog [https://aeneag.xyz](https://aeneag.xyz)

## 开始使用

由于本主题与普通 Hexo 主题有较大区别，建议请直接下载本站的源码，参考源码进行改写。

也可以创建全新的博客，通过 npm 命令安装：

~~~ 
npm i hexo-theme-resume 
~~~

然后删除多余的依赖包（重要），打开 package.json 复制并全部替换为以下内容：
~~~
{
  "name": "hexo-site",
  "private": true,
  "hexo": {
    "version": "5.2.0"
  },
  "scripts": {
    "start": "hexo server",
    "build": "node pre-deploy.js && hexo clean && hexo generate",
    "deploy": "npm run build && hexo deploy"
  },
  "engines": {
    "node": ">=8.9.0"
  },
  "dependencies": {
    "hexo": "^5.2.0",
    "hexo-autonofollow": "^1.0.1",
    "hexo-deployer-git": "^2.1.0",
    "hexo-neat": "^1.0.9",
    "hexo-renderer-ejs": "^1.0.0",
    "hexo-renderer-marked": "^3.2.0",
    "hexo-renderer-stylus": "^2.0.1",
    "hexo-server": "^1.0.0"
  }
}
~~~

然后输入 ~ npm i ~ 安装依赖包。

Wechat Official Accounts

<img style="height: 240px;width: 240px; " src="https://b3logfile.com/file/2021/11/qrcode_for_gh_6991d24e23e2_344-91ebc4df.jpg" alt="个人公众号">

Wechat

<img style="height: 240px;width: 240px; " src="https://b3logfile.com/file/2021/11/WechatIMG91-dc5e5be8.jpeg" alt="个人微信">

