[](ファイル名はコマンド名.md)
# HTML
HTML（HyperText Markup Language）は、ウェブページを作成するための標準的なマークアップ言語である。HTMLは、テキストベースの文書を構造化し、コンテンツを表示するための<b>タグ</b>を使用する。
タグは< *** >から< /*** >までを一つのブロックと見なす。
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

- **[B](b.md)** 　 太文字
- **[BODY](body.md)** 　 本コンテンツ
- **[FORM](form.md)** 　 情報を送ることができる
- **[H](h.md)** 　 見出し
- **[HEAD](head.md)** 　 ヘッダー情報
- **[HTML](html.md)** 　 HTML文と指定する
- **[P](p.md)** 　 一つの段落、文章