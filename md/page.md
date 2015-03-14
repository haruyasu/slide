## プログラマが作る
## プレゼン資料

---
### Reveal.js
マークダウンを書くだけで作成できるReveal.jsは  
スライド作成をより効率化させてくれます。

デザインは自動でやってくれるので、内容だけに集中できます。

3Dで動くエフェクトも備わっており、  
カッコいいスライドが作成できます。

---
### 使い方
ファイルをダウンロードします。  
https://github.com/hakimel/reveal.js

HTMLファイルを下記に書き直すだけで、  
マークダウン形式でスライドが作成できます。
<pre>
&lt;div class="reveal">
	&lt;div class="slides">
		&lt;section
			data-markdown="./md/page.md"
			data-separator="^---"
			data-vertical="^--">
		&lt;/section>
	&lt;/div>
&lt;/div>
</pre>

---
### Grunt
ローカルで表示するためには、Gruntを動作させます。  
「grunt serve」でサーバを起動させて確認します。

---
### PDF変換
PDFにも変換できます。

1. chromeで開いて、URLにindex.html?print-pdfを付与
2. 印刷画面を表示
3. レイアウトを横にして「pdfにして保存」を選択

---
### リモート操作
reveal.jsを使用すると、  
資料をスマホからリモート操作することができます。

プレゼンするときにものすごく便利なので、  
是非試してみて下さい。
