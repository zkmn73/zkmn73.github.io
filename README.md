

Welcome to [zkmn73's Blog](https://zkmn73.github.io/)!


A minimalist personal homepage using Markdown-formatted blog posts.


## Getting Started
### BackGround

You will need knowledge about `Ruby`, `Jekyll`, `Grunt`, `MarkDown`.

### Main diferences
- **Comments**: using [giscus](https://giscus.app/), which is a commenting system powered by GitHub Discussions. You and visitors will not need other accounts any more, e.g. Disqus, Netease etc.
- **More Simplify**: without head images.
  
### Fork to your own site:
- Files need to update:
```code
  - _config.yml # main config
  - pwa/manifest.json  # website menifest config
  - package.json  # build config
  - img  # your own images
  - about.html  # your own about page
```

### A note on Jekyll versions
GitHub Pages builds your site with its own pinned Jekyll version (currently
3.10.x via the `github-pages` gem), which can lag well behind whatever Jekyll
you have installed locally. A template/filter/tag that works when you preview
with a newer local Jekyll can still break the live build on GitHub Pages —
always sanity-check anything version-sensitive (e.g. filter arguments added
in a later Jekyll) against 3.10, or just push to a branch and watch the
Pages build run before merging to `main`.

### At Last

Feel free to fork and deploy your own site, and welcome to share and star!


## Thanks
1. Thanks to OpenSource!
2. Thanks to Web Template([Hux](https://github.com/Huxpro/huxpro.github.io), [BY](https://github.com/qiubaiying/qiubaiying.github.io))


## License
MIT License
