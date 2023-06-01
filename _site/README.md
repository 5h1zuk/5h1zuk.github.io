# 5h1zuk.github.io

技術ブログ@求職中

 * https://github.com/5h1zuk/5h1zuk.github.io

# 構築手順

 * パッケージのインストール
 
 ```
┌──(shizuku🌙tsukuyomi)-[~]
└─$ sudo apt-get install jekyll 
```

 * jekyllを使用してブログシステムを構築する

```
┌──(shizuku🌙tsukuyomi)-[~]
└─$ jekyll new 5h1zuk.github.io
```

 * git initする

```
┌──(shizuku🌙tsukuyomi)-[~/5h1zuk.github.io]
└─$ git init
```

 * gitに登録してコミットする

```
┌──(shizuku🌙tsukuyomi)-[~/5h1zuk.github.io]
└─$ git add .
┌──(shizuku🌙tsukuyomi)-[~/5h1zuk.github.io]
└─$ git commit -m '私のブログを作成'
[master (root-commit) b7ca631] 私のブログを作成
 6 files changed, 166 insertions(+)
 create mode 100644 404.html
 create mode 100644 Gemfile
 create mode 100644 _config.yml
 create mode 100644 _posts/2023-06-01-welcome-to-jekyll.markdown
 create mode 100644 about.markdown
 create mode 100644 index.markdown
 ```

 * repositoryを追加する

```
┌──(shizuku🌙tsukuyomi)-[~/5h1zuk.github.io]
└─$  git remote add origin git@github.com:5h1zuk/5h1zuk.github.io.git
```

 * ブランチをmainにしてgithubにpushする
 
```
┌──(shizuku🌙tsukuyomi)-[~/5h1zuk.github.io]
└─$ git branch -M main

┌──(shizuku🌙tsukuyomi)-[~/5h1zuk.github.io]
└─$ git push -u origin main
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 8 threads
Compressing objects: 100% (9/9), done.
Writing objects: 100% (9/9), 3.60 KiB | 3.60 MiB/s, done.
Total 9 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:5h1zuk/5h1zuk.github.io.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
```




## リファレンス

 * https://ndench.github.io/jekyll/setup-jekyll-on-github-pages