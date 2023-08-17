
`調べる`{:class="block3sensing"}ブロックメニューの`聞く`{:class="block3sensing"}ブロックと`答え`{:class="block3sensing"}ブロックを使用すると、会話を行うことができます。

![「はい」が入力された聞くダイアログ](images/ask-answer.png)

何か`聞く`{:class="block3sensing"}動作をさせたいスプライトのスクリプトにいくつかブロックを追加します。

```blocks3
ask [今日欲しいものはすべて見つかりましたか？] and wait
if <(answer) = [はい]> then
say [よかったです！] for [2] seconds
else
say [お店に商品をもっと追加する必要がありそうですね] for [2] seconds
end
```

**デバッグ:** コードと答えの選択肢が正しく書かれていることを確認してください。 選択肢を英語にする場合、大文字と小文字の区別はないので、"Yes"と"YES"は"yes"に一致します。

複数の質問を追加して、会話ができるチャットボットやノンプレイヤーキャラクターを作りましょう。

**ヒント:** 質問するスプライトを`隠す`{:class="block3looks"}と、吹き出しの代わりに入力ボックス内に質問が表示されます。

![質問が内部にある聞くダイアログ](images/ask-hidden-sprite.png)

