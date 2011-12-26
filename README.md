jekyll を使ったページのレイアウト
============================

jekyll とは？
------------
テンプレートから HTML を生成する Ruby プログラム

### インストール ###
[RubyGems を用いてインストール](https://github.com/mojombo/jekyll/wiki/Install)

	gem install jekyll

### 構成ファイル ###
[基本構成](https://github.com/mojombo/jekyll/wiki/Usage) は以下の通り。

	.
	├─ _config.yml
	├─ _layouts
	│   ├─ default.html
	│   ├─ post.html
	│   └─ ...
	├─ _includes
	│   ├─ header.html
	│   ├─ footer.html
	│   └─ ...
	├─ _posts
	│   ├─ YYYY-MM-DD-title-of-the-post.(md | textile)
	│   └─ ...
	├─ _site
	└─ index.(md | textile)

+ **_config.yml**  

+ **_layouts**  

+ **_includes**  

+ **_posts**  

+ **_site**  

+ **index.md**

GitHub Page
-----------
GitHub Page for [tokkonopapa/Markdown](http://tokkonopapa.github.com/Markdown/)
