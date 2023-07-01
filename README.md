# tecma-blog

https://tecmah.com
# local start

## git clone
this project clone

## node install
nodeはnvm推奨(権限エラー回避の為)
VOLTAで管理していますが任意で選んでください。

```
npm install hexo-cli -g
npm install hexo-generator-sitemap --save
npm install hexo-deployer-git --save

```

## 起動

```cc
hexo clean && hexo s --debug
hexo clean && hexo generate
```

http://localhost:4000 で起動するか確認する


# deploy
_config.ymlで管理されている。


```

hexo clean && hexo deploy --generate
gcloud app deploy

```

# congfigに関して
configはHexoとNextのものを編集することになります。

#　設定image
tecma-blog/node_modules/hexo-theme-next/source/images/avatar.gif



# 新規記事の作成

```
hexo new [layout] <記事名>
hexo new post "HexoでgoogleSerchConsoleの登録"
```
=======


## github pages



# local start

hexo server


# 記事の管理をmasterブランチに変更


