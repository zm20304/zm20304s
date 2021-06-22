# zm20304s
情報篤学機構1
<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <title> Web開発の練習１</title>
  <link rel="stylesheet" href="mystyle.css"> <!--この行を追加-->
  <!--<script src="myjs.js"></script>-->
</head>
<body>
  <!--文字の大きさの練習-->

  練習問題２．３

<h1>Hello World</h1>
  <h2>Hello World</h2>
  <h3>Hello World</h3>
  <ol>
      <li>ほげほげ</li>
      <li>ほにゃらら</li>
  </ol>
  <script src="myjs.js"></script>
 練習問題2.3
<dl><dt>作者</dt>
 <dd>ジョン</dd>
 <dd>ポール</dd>
 <dd>ジョージ</dd>
 <dd>リンゴ</dd>
</dl>
<dl>
<dt lang="ja"><dfn>色</dfn></dt>
<dt lang="en-US"><dfn>colour</dfn></dt>
<dt lang="en-GB"><dfn>colour</dfn></dt>
<dd>可視光線の波長の長短によってい人が視覚で感じ分けられる色覚・色刺激のこと</dd>
</dl>
<p>ゲームの得点は以下の順序で計算されます。
  </p>
  <dl>
    <dt>金貨を獲得している場合</dt>
<dd>金貨一枚につき１０ポイント加算されます。
</dd>
<dt>銀貨獲得している場合</dt>
<dd>銀貨一枚につき１ポイント加算されます。</dd>
<dt>枚数にかかわらず、金貨と銀貨を両方獲得している場合</dt>
<dd>ボーナスポイントとして２０ポイント加算されます。</dd>
<dt>それ以外の場合</dt>
<dd>ポイントは加算されません。</dd>
</dl>
練習問題2.4
<table>
<caption>
<strong>お寿司をどこで食べるか？その長所と短所</strong>
<details>
<summary>このテーブルの説明</summary>
<p>以下のテーブルでは、２番目のカラムに寿司店のタイプが入れられています。
  その左側にそのようなタイプのお店でお寿司を食べる場合の長所が、右側に短所が入れられています。</p>
</details>
</caption>
<thead>
<tr><th>長所</th><th>どこで食べるか</th><th>短所</th></tr>
</thead>
<tbody>
  <tr><td>ネタにこだわり、技術が素晴らしい</td><th>銀座の高級店 
  </th><td>値段が時価で不安、予約が必要</td></tr>
  <tr><td>値段が良心的、気軽に手に取れる</td><th>回転寿司
  </th><td>ネタが解凍もの、休みの日は混む</td></tr>
</tbody>
</table> 
<table>
<caption>
<strong>お寿司をどこで食べるか？その長所と短所</strong>
</caption>
<thead>
<tr><th>どこで食べるか</th><th>長所</th><th>短所 
</th></tr>
</thead>
<tbody>
<tr><th>銀座の高級店</th><td>ネタにこだわり、技術が素晴らしい
</td><td>値段が時価で不安、予約が必要</td></tr>
<tr><th>回転寿司</th><td>値段が良心的、気軽に手に取れる
</td><td>ネタが解凍もの、休みの日は混む</td></tr>
</tbody>
</table>]
練習問題2.5
  <ul><li>参考資料を調べ、次のように表示されるHTMLを書きなさい:
  <p
 style="margin:1ex">x<sup>2</sup>+y<sup>2</sup>=z<sup>2</sup>
 <br/>
 この授業は<b>情報特講1</b>で、<s>眠くなる</s>大変興味深い内容で
す。<br/>
<bdo dir="rtl">昔の日本語は右から左に書いていました。</bdo></p>
</li>
</ul>
練習問題2.7
<form action="xxx.php" method="post"><label>メール(type=email):</label><input type="submit" value="送信"></form>
<form action="xxx.php" method="post"><label>URL(type="url" name="url"></label><input type="submit" value="送信"></form>
<form action="xxx.php" method="post"><label>検索(type="search"):<input type="search" name="search"></label><input type="submit" value="送信"></form>
<form action="xxx.php" method="post"><label>電話(type="telephone"):<input type="tel" name="tel"></label><input type="submit" value="送信"></form>
<form action="xxx.php" method="post"><label>数値(type=number"):<input type="number" name="number"></label><input type="submit" value="送信"></form>
<form action="xxx.php" method="post"><label>日付(type="date"):<input type="date" name="date"></label><input type="submit" value="送信"></form>
<form action="xxx.php" method="post"><label>ローカル日時（type="datetime"-local):<input type="datetime-local" name="datetime-local"></label><input type="submit" value=”送信”></form>
<form action="xxx.php" method="post"><label>月(type="month"):<input type="month" name="month"></label><input type="submit" value="送信"></form>
<form action="xxx.php" method="post"><label>週(type"week"):<input type="week" name="week"></label><input type="submit" value="送信"></form>
<form action="xxx.php" method="post"><label>時間(type="time"):<input type="time" name="time"></label><input type="submit" value="送信"></form>
<form action="xxx.php" method="post"><label>レンジ(type="range"):<input type="range" name="range"></label><input type="submit" value="送信"></form>
<form action="xxx.php" method="post"><label>色(type="colour"):<input type="color" name="color"></label><input type="submit" value="送信"></form>
<p><label>名前:<input type="text" name="name" size="30" maxlength="20"></label></p>
<p><label>パスワード:<input type="password" name="pass" size="6" maxlength="4"></label></p>
<p>学年:
<label><input type="radio" name="gakuen" value="1">1年生</label>
<label><input type="radio" name="gakuen" value="2">2年生</label>
<label><input type="radio" name="gakuen" value="3">3年生</label>
<label><input type="radio" name="gakuen" value="4">4年生</label>
<label><input type="radio" name="gakuen" value="5">5年生</label>
<label><input type="radio" name="gakuen" value="6">6年生</label>
</p>
<p>好きな課目：<label><input type="checkbox" name="kamoku" value="kokugo">国語</label><label><input type="checkbox" name="kamoku" value="eigo">英語</label><label><input type="checkbox" name="kamoku" value="sansu">算数</label><label><input type="checkbox" name="kamoku" value="rika">理科</label><label><input type="checkbox" name="kamoku" value="syakai">社会</label><label><input type="checkbox" name="kamoku" value="taiiku">体育</label></p><p><label>宿題ファイル：<input type="file" name="syukudai"></label></p><p><input type="submit" value="送信"><input type="reset" value="リセット"></p>
著作権高校講座HOME>> 社会と情報>> 第14回法律と個人の責任考えよう著作権https://www.nhk.or.jp/kokokoza/tv/syakaijouhou/archive/chapter014.html•18歳からの著作権入門–CNET Japan•ファイル共有ソフト等を使用した著作権法違反事件の一斉集中取締りの実施について–警察庁•WELQなどのキュレーションメディアを著作権法の観点から分析してみた–柿沼太一, STORIA法律事務所

練習問題３.１

<a href="a.html">相対パスでリンクします</a><br>
<a
href="https://www.josai.ac.jp/education/managment/index.html">絶対パスで城西大学経営学部へリンクします。</a><br>
<a href="maito:zm99999@josai.ac.jp">自分宛メール(自分のメールアドレスを入力)</a><br>
<a href="https://www.josai.ac.jp/education/managment/index.html/"><img src="./image/keiei_small.jpg" alt="城西大学ホームページ"></a>
練習問題3.2
<a href="a.html" target="_blank">別画面を開いてリンクします</a><br><a href="a.html" target="_self">リンク元と同じフレームにリンクします</a><br><a href="a.html" target="_parent">ひとつ上の親フレームにリンクします</a><br><a href="a.html" target="_top">フレームをすべて解除してリンクします</a><br><a href="a.html" target="abc">abcという名前のフレームにリンクします</a><br>
練習問題3.3
<a id="abc">ここがabcの場所</a>
<p>アンカータグの練習です。</p><a id=“def”>ここがdefの場所</a>
ファイルの途中にidでabcという名前を付けます。<a href="#abc">abcと名前を付けた場所へリンクします</a><br><a href="a.html#def">別ファイルの名前を付けた場所へリンクします</a>
練習問題3.4
<aside class=“ad”><h1>広報</h1><a href=“https://www.josai.ac.jp/club/jyosisofuto.html”><section><h1>城西大学女子ソフトボール部</h1><p>女子ソフトボール部＜全日本総合女子ソフトボール選手権大会出場決定！＞</p></section></a><a href=“https://www.josai.ac.jp/news/20200615-04.html”><section><h1>城西大学JOSAI SPORTS FEILD </h1><p> JOSAI SPORTS FIELD建設・整備が進んでいます【城西大学坂戸キャンパス】</p><p>城西大学坂戸キャンパスの北側の毛呂山町下川原沼に、サッカー場２面、ソフトボール場１面、アップダウンのあるランニングコース、管理施設にはシャワー室やミーティングルームなどを備えた新しいグラウンド"JOSAI SPORTS FEILD" が完成間近です。使用開始は、2020年9月の予定です。</p></section></a></aside>
練習問題3.5
<nav><ul><li><a href=“https://www.josai.ac.jp/club/jyosisofuto.html”>女子ソフトボール部</a></li><li><a href=“https://www.josai.ac.jp/club/ekiden_hakone.html”>男子駅伝部</a></li><li><a href=“https://www.josai.ac.jp/club/ekiden_joshiekiden.html”>女子駅伝部</a></li><li><a>クラブ・サークル活動</a></li></ul></nav> 
