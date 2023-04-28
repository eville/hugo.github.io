---
title: "How to start?"
date: 2023-04-28T00:31:34+03:00
draft: false
---

#### If you wish your blog to look like this:

![Paperesque theme example](/images/paperesque_style_example.jpg)


#### Use command line to create and start your brand new site with paperesque theme:

```hugo new site quickstart
cd quickstart
git init
git submodule add https://github.com/capnfabs/paperesque.git
echo "theme = 'paperesque'" >> config.toml
hugo server
```

