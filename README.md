# ①課題番号-プロダクト名

kadai01_janken

## ②課題内容（どんな作品か）

大阪のおすすめの飲み屋の診断ができるアプリ。

## ③DEMO

https://723kb.github.io/kadai01_janken/

## ④作ったアプリケーション用のIDまたはPasswordがある場合

ID: 今回はなし
PW: 今回はなし

## ⑤工夫した点・こだわった点

ロジックをしっかり組むことに重点を置いて課題に取り組んだ。そのため分岐の数を多めにし、エリアや選んだ選択肢によって次に表示させる内容を変えるという点にこだわった。
文字だけだと見る側からはわかりにくいと思い、写真も一緒に表示できるように工夫した。
前回できなかったレスポンシブデザインに取り組んだ。

## ⑥難しかった点・次回トライしたいこと(又は機能)

それぞれのエリアや直前に選んだ選択肢によって次に表示させる質問や選択肢を変更しており、1つ作ったものをコピペで流用することができない部分もあり頭を使った。
おすすめのお店の名前を表示させるところまでは比較的簡単にできたが、一緒に写真を表示させることがかなり難しく時間を要した。本当は２枚の写真の間に余白を設けたかったが、なぜかできず諦めてしまった。
また写真は一度リロードをしないと前回の写真が残ってしまい、カオスなことになってしまう。現時点では「やりなおす」ボタンを作り対処したが、今後この課題をうまく解消したいと思う。
店名や写真と一緒にマップやおすすめのメニューなどお店の詳細情報も表示させたかったが、うまくできなかったため今後チャレンジしたい。

## ⑦質問・疑問・感想、シェアしたいこと等なんでも

[質問]　今回は分岐の数が多くひとまず上から順にロジックを組んでいったが、途中で混乱することも多かった。複雑な分岐処理を記載したい場合は、どのようにコードを書く（組み立てる）のが良いのか？

[感想]今回はTailwind CSSをCDNで記載したせいか、少し動作が重たいような印象を受けた。　if文のなかにさらにif文を入れることができることに驚いた。これによって割といろいろなものが作れるのではないかと思った。
分岐が多くなると自分の頭も混乱してしまい、エラーが発生したときに全容が掴みにくく難しく感じた。ただ全体的にできることの幅が広がり楽しく取り組むことができ、完成したときにはとても達成感があった。

[参考記事]
  1. [https://x.gd/zqsC0] エラーの種類を調べるときに使用した。
  2. [https://jp.xmind.net/]　分岐処理を理解しやすくするためにXmindを使用した。
  3. [https://www.sejuku.net/blog/23942#index_id6] ===以外にも＆＆を使用したので。nullとundefinedの比較についても勉強になった。
  4. [https://wagtechblog.com/programing/back-next-reload.html] 戻る・進む・更新ボタンは今後の課題制作でも使う機会が多いかと思う。
