---
title: Hello World
---
Welcome to [Hexo](https://hexo.io/)! This is your very first post. Check [documentation](https://hexo.io/docs/) for more info. If you get any problems when using Hexo, you can find the answer in [troubleshooting](https://hexo.io/docs/troubleshooting.html) or you can ask me on [GitHub](https://github.com/hexojs/hexo/issues).

## Quick Start

### Create a new post

``` bash
$ hexo new "My New Post"
```

More info: [Writing](https://hexo.io/docs/writing.html)

### Run server

``` bash
$ hexo server
```

More info: [Server](https://hexo.io/docs/server.html)

### Generate static files

``` bash
$ hexo generate
```

More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to remote sites

``` bash
$ hexo deploy
```

More info: [Deployment](https://hexo.io/docs/one-command-deployment.html)

<div id="gitalk-container"></div>
<link rel="stylesheet" href="https://unpkg.com/gitalk/dist/gitalk.css">
<script src="https://unpkg.com/gitalk/dist/gitalk.min.js"></script>
<script>
  var gitalk = new Gitalk({
    clientID: 'fab417f36e83e1fa2d62',
    clientSecret: '634ed3d47f92778bdb5c7fa833eded3dac79de93',
    repo: 'gitalk-comments',
    owner: 'youkaifeng',
    admin:  ['youkaifeng'],
    id: location.pathname,      // Ensure uniqueness and len
    language:'zh-CN', // 语言
    distractionFreeMode: false,  // Facebook-like distraction
    proxy: 'https://github.com/login/oauth/access_token',
  })
  gitalk.render('gitalk-container')
</script>