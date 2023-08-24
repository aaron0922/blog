# Blog

## prerequirement
```sh
# 1. install hugo and create hugo site
$ brew install hugo
$ hugo new site myblog --format yaml

# 2. add themes
$ cd myblog
$ git submodule add --depth=1 https://github.com/adityatelange/hugo-PaperMod.git themes/PaperMod
$ git submodule update --init --recursive

# 3. update myblog/hugo.yaml as https://github.com/adityatelange/hugo-PaperMod/wiki/Installation

# 4. update baseURL of the myblog/hugo.yaml to "http://<github user>.github.io/<github repo>"
```

## Build
```sh
$ cd myblog
$ hugo -d ../docs
```

## Develop
```sh
$ cd myblog
$ hugo server
```
 
 ## Reference
 1. https://github.com/adityatelange/hugo-PaperMod/wiki/Installation

