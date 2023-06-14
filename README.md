# bicpema-blog

### Setup

```bash
$ git clone git@github.com:tooooofu24/bicpema-blog.git
```

[Hugo](https://gohugo.io/)のインストールが必要。

https://gohugo.io/installation/

インストールが終わったら`hugo`コマンドが使えるか確認する。

```bash
$ hugo version
hugo v0.112.5+extended darwin/amd64 BuildDate=unknown
```

`hugo`のインストールが完了していれば、以下のコマンドでローカルサーバーが立ち上がる。

```
$ hugo server -D
```

### 使い方

記事の追加

```
$ hugo new post/[記事のタイトル(英語)]/index.md
```

マークダウンの記法は以下が参考になる

https://github.com/CaiJimmy/hugo-theme-stack/tree/master/exampleSite/content/post

各投稿の`Suggest Changes`をクリックすることで記事の Markdown を確認できる。

https://github.com/adityatelange/hugo-PaperMod/tree/exampleSite/content/posts

### その他

- `content/post`,`content/tags`以外は基本的にはいじらない。
- ページのテンプレート部分で修正したい場合は @tooooofu24 まで。
- push すると自動でデプロイされる。
- デプロイの状況は[こちら](https://github.com/tooooofu24/bicpema-blog/actions)で確認できる。
- デプロイ先 URL → https://bicpema-blog.web.app/
