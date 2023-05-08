# CDN 资源服务

日常一些公共文件放此仓库，然后配合 [jsdelivr](https://github.com/jsdelivr/jsdelivr) 获得一份 cdn 链接

CDN 地址规则: `https://cdn.jsdelivr.net/gh/你的用户名/你的仓库名@发布的版本号/文件路径`
- 版本号我们始终不传，始终默认使用最新版本 
- gh 表示 github 仓库类型

示例：
对于仓库的 `/js/hello.js` 文件，其 CDN 地址为 [https://cdn.jsdelivr.net/gh/francecil-public/cdn-resouce/js/hello.js](https://cdn.jsdelivr.net/gh/francecil-public/cdn-resouce/js/hello.js)

# 可视化服务

通过传统方法上传文件较为繁琐，需要手动执行 commit + push

这里我们选择 [PicX](https://picx.xpoet.cn/) 来进行图片上传。

具体步骤即在平台配置 github token ，后续在 PicX 平台上传文件会自动同步到本仓库