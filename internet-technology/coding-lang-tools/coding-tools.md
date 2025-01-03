## 常用CDN

1. jsdelivr：免费、高速且稳定的 CDN 服务, 支持github文件，提供了 NPM、Github、WordPress Plugin 和其他自定义网站的资源镜像

   国内访问很慢(请求失败，听说是2023年初ICP备案被吊销)， 可用 https://jsdelivr.codeqihan.com/ 加快访问

2. Staticfile CDN: https://staticfile.org/, CDN加速由七牛云提供，访问速度很快

3. 字节跳动: https://cdn.bytedance.com/, 字节跳动静态资源公共库

4. loli, https://cdnjs.loli.net. Cloudflare国外节点，访问速度比较一般，可以应急使用

5. cdnjs/UNPKG, 国外的老牌CDN，国内访问速度就一般了

6. statically, https://statically.io/ ，支持加速GitHub、GitLab的开源仓库

> 链接格式：
>
> Serve file from GitHub
>
> https://cdn.statically.io/gh/:user/:repo/:tag/:file
>
> Serve file from GitLab
>
> https://cdn.statically.io/gl/:user/:repo/:tag/:file

## JSdeliver

GitHub：https://github.com/{{owner}}/{{repo}}/raw/{{branch}}/{{path}} 

A free, fast, and reliable Open Source CDN for npm, GitHub, Javascript, and ESM

格式：https://cdn.jsdelivr.net/gh/{{owner}}/{{repo}}@{{branch}}/{{path}}

Github: https://github.com/jsdelivr/jsdelivr

https://www.jsdelivr.com/

jsdelivr 镜像站:

https://jsd.cdn.zzko.cn/gh/{{owner}}/{{repo}}@{{branch}}/{{path}}

ChinaJsDelivr Github: https://github.com/54ayao/Chinajsdelivr

> 境内站 https://jsd.cdn.zzko.cn/ 
>
> 国际站 https://cdn.jsdelivr.us/ cloudflare 节点
>
> 国际站 https://cdn.jsdelivr.ren/ gcore节点

## Staticaly

https://cdn.staticaly.com/gh/{{owner}}/{{repo}}@{{branch}}/{{path}}

## Velocity

[![website_official](https://gitbook07.oss-cn-hangzhou.aliyuncs.com/website_official.svg)](http://velocity.silverlakesoftware.com/)

  离线的API文档工具. \(类似macOS上的[Dash](https://kapeli.com/dash)\)

