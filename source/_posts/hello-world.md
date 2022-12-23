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
    clientID: 'd25d2a6553f2fcd0c4cd',
    clientSecret: 'c08771a9fec54d35243d046766c79064a8db56a2',
    repo: 'youkaifeng.github.io',
    owner: 'youkaifeng',
    admin:  ['youkaifeng'],
    id: location.pathname,      // Ensure uniqueness and len
    distractionFreeMode: false  // Facebook-like distraction
  })
  gitalk.render('gitalk-container')
</script>