# HTML
<　h　>→文章の見出し、テキストは改行される。

<　a　>→リンク
  
<　href　>→<　a　>要素にリンクの飛び先を指定する。<a href="url">と書く。urlはダブルクォーテーション（"）で囲む
  
/→終了タグ
  
h１やh２などの数字は小さければ小さいほど文字は大きくなる
  
<　p　>→段落、テキストは改行される。
  
<!-- -->→コメントとして書かれたテキストはブラウザには表示されないため、メモとして使うことが可能。
  
<　img　>→画像の表示に使用。<　img src="url"　>と書く
  
<　li　>→リストの作成に使用。箇条書きにしたいテキストをそれぞれ<　li　>タグで囲む。list-styleプロパティでnoneを指定すると先頭のマークを消せる。
  
<　ul　>→<　ul　>要素で囲むと、黒点が先頭につく
  
< ol >→<　ol　>要素で囲むと、数字が連番でつく
  
囲む方の要素を親要素(li)、囲まれる要素を子要素と呼ぶ。(ul,ol)
  
また要素を要素で囲むことを入れ子と言い、入れ子構造の要素がある場合は、インデント（字下げ）をする。

<head>要素→ページに関する情報(①文字コードの指定、②ページのタイトルの設定、③CSSの読み込みなど)
  
<meta charset="utf-8">→そのページの文字コードをUTF-8に指定することができる（HTMLで推奨されている文字コード）①
  
<title>→ページのタイトルを指定②
  
<link rel="stylesheet">→HTMLからCSSを読み込む。<link rel="stylesheet" href="stylesheet.css">のように、href属性で読み込むCSSファイルを指定する
  
<body>要素→実際に表示したい内容
  
<!DOCTYPE html>→HTMLのバージョンを宣言
  
<div>→要素をグループ化するために使用する

class→要素（タグ）に名前をつけることが可能。class名でCSSを指定する場合、先頭にドット「.」が必要。

<span>要素→文中の一部にCSSを適用させたい時に適用

<input>要素→１行のテキスト入力を受け取るための要素
  
また<input type = "submit">とすることで入力欄ではなく、送信ボタンになる。さらにvalue属性に任意の値を指定することで、ボタンに表示されるテキストを変更することができます。
  
<textarea>→要素は複数行のテキスト入力を受け取るための要素

inputとtextareaはcssにて,で区切ることで同じcssを適用できる
