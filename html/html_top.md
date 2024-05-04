[](ファイル名はコマンド名.md)
# HTML
HTML（HyperText Markup Language）は、ウェブページを作成するための標準的なマークアップ言語である。HTMLは、テキストベースの文書を構造化し、コンテンツを表示するための<b>タグ</b>を使用する。
タグは< hoge >から< /hoge >までを一つのブロックと見なす。
<b>そのため大文字/小文字の区別や空白や改行も無視される</b>。

記述例 [](変更しない)
  
  ```
<!-- saved from url=(0035)http://api.fml.org/dist/lsform.html -->
<html>
    <head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8"></head>
    <body>
        <p>SHOPPING CART</p>
        <form method="POST" action="http://api.fml.org/api/lsform/v1">
            <p>item-01<input name="item-01" type="text"></p>
            <p>item-02<input name="item-02" type="text"></p>
            <p>item-03<input name="item-03" type="text"></p>
            <p><input type="submit" value="buy"></p>
        </form>
    </body>
</html>
  ```

表示結果　[](変更しない)

![](../goto/html_top.png)

### タグ一覧

<h2>[B](b.md)</h2>太文字
<h2>[BODY](b.md)</h2>メインコンテンツ
<h2>[FORM](form.md)</h2>情報を送ることができる
<h2>[H](h.md)</h2>見出し
<h2>[HEAD](head.md)</h2>ヘッダー情報
<h2>[HTML](html.md)</h2>HTML文と指定する
<h2>[P](p.md)</h2>一つの段落、文章
