# blog-hugo
Hugo website

```
hugo new site blog-hugo --format yaml
cd blog-hugo
git submodule add --depth=1 https://github.com/adityatelange/hugo-PaperMod.git themes/PaperMod
hugo new posts/my-first-post.md
hugo server
```

hugo.yaml
```
baseURL: https://example.org/
languageCode: en-us
title: My New Hugo Site
theme: ["PaperMod"]
```