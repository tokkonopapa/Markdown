プロジェクト・タイトル
======================
ここにプロジェクトの概要を書きます。
行末にスペースを2つ入れると  
改行されます。

段落を分けるには、[空行](http://example.com/) を入れます。

使い方
------
### インライン ###
インラインのコードは、**バッククォート** (`` ` ``) で囲みます。

### ブロックレベル ###
    <script type="text/javascript" src="jquery.min.js"></script>
    <script type="text/javascript">
    $(function() {
        alert($); /* 先頭に4文字のスペース、
                     もしくはタブを挿入します */
    });
    </script>

パラメータの解説
----------------
リストの間に空行を挟むと、それぞれのリストに `<p>` タグが挿入され、行間が
広くなります。

    def MyFunction(param1, param2, ...)

+   `param1` :  
    _パラメータ1_ の説明

+   `param2` :  
    _パラメータ2_ の説明

関連情報
--------
### リンク、ネストしたリスト
1. [リンク1](http://example.com/ "リンクのタイトル")
    * ![画像1](http://github.com/unicorn.png "画像のタイトル")
2. [リンク2][link]
    - [![画像2][image]](https://github.com/)

  [link]: http://example.com/ "インデックス型のリンク"
  [image]: http://github.com/github.png "インデックス型の画像"

### 引用、ネストした引用
> これは引用です。
> 
> > スペースを挟んで `>` を重ねると、引用の中で引用ができますが、
> > GitHubの場合、1行前に空の引用が無いと、正しくマークアップされません。

ライセンス
----------
Copyright &copy; 2011 xxxxxx  
Licensed under the [Apache License, Version 2.0][Apache]  
Distributed under the [MIT License][mit].  
Dual licensed under the [MIT license][MIT] and [GPL license][GPL].

[Apache]: http://www.apache.org/licenses/LICENSE-2.0
[MIT]: http://www.opensource.org/licenses/mit-license.php
[GPL]: http://www.gnu.org/licenses/gpl.html
