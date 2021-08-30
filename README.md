# tech-night-assets

youtube版TechNightで使う画面要素を配置するRepo。OBSでgithub pagesをブラウザで読み込んで使ってください。

## ディレクトリ構造

### `/commons`

各回共通で使うhtmlを配置するディレクトリ

### `/no_xx`

タイトルなど、各回で特別に用意するものをまとめるディレクトリ

### `/styles`

共通StyleSheetを配置するディレクトリ

### `/templates`

各回用のディレクトリを自動生成するときにコピーするファイルが入っているディレクトリ

## 新しいエピソードのディレクトリを作るときは

```bash
$ make generate_new_episode name=hoge
```

のように実行すると `/no_hoge` とテンプレートファイルがコピーされるのでこの中のファイルを更新してcommitすること
