---
title: "git diff のカラー設定を変更する"
date: 2017-12-04T23:30:30+09:00
description: Git diff colors setting
tags: ['git']
isCJKLanguage: true
showComments: true
---

普段ターミナルの文字色を緑色にして使っているが、git の diff color も緑色で、変更箇所がぜんぜんハイライトされていなかったのでカラー設定を調整した。

`~/.gitconfig` に以下設定を追加

```
[color "diff"]
  meta = green
  frag = blue
  old = red
  new = white
```

参考記事にはターミナルのデフォルトカラーを使用する設定もあったが、ちょこまかカラーいじってるのでいったん手動設定にする。


### 参考

[git diffのカラー設定を変更する](http://orangeclover.hatenablog.com/entry/20120920/1348086391)
