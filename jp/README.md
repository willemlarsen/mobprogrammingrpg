# モブプログラミング：ロールプレイングゲーム
 
## 本資料について
MOB PROGRAMMING: THE ROLE PLAYING GAME　を日本語にしつつ、適宜リモートワークでも使えるように修正しました。
 
## 序文
by Willem Larsen CC-BY-SA-NC 2016
 
Powered by the Apocalypse  - BigBadCon 2016にインスパイアされたことに感謝します。
 
## このゲームは
モブプログラミングがどういうものなのかを知り、ゲームを通して疑似経験を積むことで、現場に楽しくモブプログラミングを導入できるようにするきっかけになります。
 
ゲームを行うに当たって、モブの経験は必要ありません。
初めてのモブワークを楽しんでください。

## ゲームマスターへ
まず最初に、このゲームのテストプレイにご協力いただき、ありがとうございます。
あなたの第一の義務は、プレイしている全員が「優しさ」「思いやり」「尊敬」の気持ちを持って接することです。

このゲームを初めて運営するときは、ぎこちないでしょう。それを受け入れてください。
しかし、基本的なルールである、常に「親切」「思いやり」「尊敬」の気持ちを持って接することは譲らないでください。
 
## ゲームの要件
3人以上集めてモブを作ります（上限は不明）。
ゲームマスターがファシリテートします。
 
※ゲームを作った人は最大15人のモブでプレイしたことがあるそうです。  
※モブの経験は必要ありません。
 
- このモブの中の少なくとも1人は、テスト駆動開発にある程度慣れている必要があります。
- すべてのプレイヤーが快適に見ることができるような大きな共有スクリーンを用意します。大画面のテレビはとても効果的です
- 共有キーボードを1つ用意する (風邪をうつさないように、消毒液を用意することも検討してください。)
- ハサミとテープ（スコッチ、マスキング、ポスターテープなど）を1、2組用意する。
- レベル1のロールシートは各プレイヤーに3枚ずつ、レベル2のロールシートは最低1枚プリントアウトしてください

## リモートでやる場合
- リモートメンバーでやる場合はエディタの切り替えが発生しないように、VSCodeのLiveShareなどを使うことをおすすめします
- コンポーネント用にJambordやMiro等で事前準備しておくと良いでしょう

## プレイヤーがプレイする前に
- IDEに、セッションに参加する少なくとも1人が使えるプログラミング言語のテストファイルをセットアップしてください
- その後、IDE上で1つのテストが正常に失敗している状態を作ってください
- ドライバー、ナビゲーター、モバーの3つの役割のローテーションの方法をいくつか決めてください
- あなたは3分ごとにドライバーとナビゲーターのポジションのローテーションをリードします。ドライバーは右側に移動して新しいナビゲーターになり、ナビゲーターは一般的なモバーになります。一定の順序で一貫してローテーションを行います
 
- ローテーションを忘れないようにMob Timerをインストールし、使用してください（任意）
 
- モブバッジの駐車場であるモブスクワッドゾーンを作り、ラベルを貼ります。白紙の壁やホワイトボードに、プレイヤー個人が完成させたモブバッジを貼ります。これはグループの業績となり、メンバーが完成させたロールシートの総数となります

## 題材
まずは非常に簡単なFizzBuzzをやってみると良いでしょう。  
ただし、モブワークのメリットを実感するには難易度が足りないかもしれません。  
その場合は[CodeKata](http://codekata.com/) や自分が開発しているプロダクトに新しい機能
を付けるなどで題材を用意するのが良いでしょう。

 

 
## ゲームの流れ
### 最初の説明  
ゲームマスターは以下を音読してください。
```
皆さんこんにちは。
私たちは「モブプログラミング：ロールプレイングゲーム」をプレイするためにここに来ました。
 
まず、最も重要なルールを説明します。
 
「私たちは常に「親切」「思いやり」「尊敬」の気持ちを持ってお互いに接すること」
 
困難な状況に陥ったとき、このことを忘れないようにするために、力を貸していただけないでしょうか？[返信を待つ）... 
 
モブプログラミングは、コードの品質を上げ、障害を取り除くために使われる開発手法です。
実際には、レースカーというよりブルドーザーのように、止められない、徹底的なものである。
それがモブプログラミングです!
 
「ロールシート」とは、役割のアイコンと説明が書かれたシートのことで、私たちはこう呼んでいます。
 
現在、ロールシートは3段階あり、数えるほどしかありません。
今回はレベル1についてだけ説明します。
 
ローテーションのどこにいるかによって、適切なロールシートを使用することになります。
 
キーボードの前にいる人はドライバーなので、ドライバーのロールシートを記入することになります。
もしあなたがドライバーの右側に座っているなら、あなたはナビゲーターです。
ナビゲーターはナビゲーターのロールシートを記入することになります。
 
それ以外の人はMobberロールシートに取り組むことになります。
 
このゲームの目的は2つあります。
 
1．ロールシートに書かれた役割をできるだけ正確に「体現」することで、立派なモブになることです。
 
2．このセッションでできる限り多くのロールシートを完成させるために、お互いに助け合いながら「グループのモブを作る」ことです。
 
親切、思いやり、尊敬の念を持ってゲームに取り組みましょう！
ゲームが終わる頃には、あなたは歴史に残る偉大なモブの仲間入りをすることができます。

```
 
### 各プレイヤーがロールシートを選択した後
```
さあ、自分のロールシートを見てください。
どのような行動をとったかを判断し、チェックボックスにチェックを入れるのはあなた次第です。XP(Experience Points)がもらえる行動をしたと決めたら、その内容をグループ内で大声で発表し、ボックスにチェックを入れてください。
すべてのボックスにチェックを入れたら、ロールシートを交換することができますが、それについては、その時に詳しく説明します。
ローテーションの順番を決め、ドライバー／ナビゲーター／モブというように決めたポジションに就いてもらう。
```
 
### タイマーを始める前にプレイヤーに伝る
```
役割を見ればわかるように、ドライバーの仕事はナビゲーターが指示したものをタイプすることです。
ナビゲーターの仕事は、モブのアイデアを選別し、ドライバーに何をタイプすればよいかを指示することです。

このゲームでは、コーディングに夢中になると、自分の役割を忘れてしまうことがあります。
そこで、ナビゲーターの右隣にいる人は、ナビゲーターがXPの行動を完了したときに、チェックボックスにチェックを入れることを忘れないようにサポートすることが仕事です。
ドライバーの左の人も同じように、ドライバーが行動を完了し、ボックスにチェックを入れることができたときに、ドライバーに思い出させるのが仕事です。
私たちの目標は、「1時間でできるだけ多くの役割を終え、過去の記録を破ることです（2018年5月現在の記録は1時間で39バッジです）」と覚えておいてください。
何か質問はありますか？
```

### モブ開始
3分タイマーをスタートさせます。  
タイマーが鳴ったらドライバーはナビゲーター、ナビゲーターはモブメンバー、次のモブメンバーはドライバーと、ポジションを交代してください。  
プレイが始まったら、「優しさ」「思いやり」「尊敬」があるかどうかをメンバーゲーム参加者同士で確認してください。
 
もし、「優しさ」「思いやり」「尊敬」が欠けていることに気づいたら、モブに向かって「優しさをお願いします！」「思いやりをお願いします！」「尊敬をお願いします！」と声をかけてください。
 
ローテーションごとに、作業を停止し、プレイヤーに以下の質問をします（回答はメモしておいてください）。
 
```
何が印象に残りましたか？コーディングの課題、または全体的なゲームプレイについて何か気づきましたか？何か苦労していることはありますか？
```
 
このディスカッションに5分以上かけてはいけません。
簡潔にしてメモを取り、タイマーを再スタートして、次のローテーションが終わったらこれを繰り返します。
 
 
すべての役割はプレーヤーに付属するものです。ローテーションによって所有者が変わることはありません。
ドライバーとナビゲーターのロールシートはプレーヤーがその役割になっている時だけ取り出して使用し、XPを獲得することができます。ドライバーやナビゲーターの役割になっている時はモブのロールシートはしまってください。(したがって、ローテーションを再開するまで、これらのロールに対してXPを得ることができなくなります)
逆に、モブになっている時はドライバーとナビゲーターのロールシートはしまい、モブのロールシートを出して、XPを付けてください。
 
### プレイヤーがロールシートを完成させたとき
アイコンバッジを点線で切り取り、裏にテープを貼って、モブバッジ駐車場に貼ってもらいましょう。
このゾーンはグループのモブ隊で、ロールシートを仕上げると様々なバッジで埋め尽くされます。
切り取ったロールシートはそのままにしておいてもかまいません。
ロールシートに書かれている指示に従い、その動きによってXPを獲得することができます。
 
### 集計
1時間のローテーションの後（時間によってはそれ以下でも可）
1時間くらいローテーションを回したら、ゲーム終了です。
手元にあるバッジを数えましょう。
これがモブのゲームの得点になります。
 
### レトロスペクティブ
10～15分程度、このゲームをやってみた振り返りをしてみましょう。
- 良かったこと、楽しかったことは何ですか？
- 逆に悪かった点、楽しくなかったことは何ですか？
 - ロールシートを完成させた人は、どんな点が良かったのでしょうか？
- 次回はどのようにプレイしますか？
 
おしまい！

はい！これでゲーム終了です。

楽しんでもらえたら幸いです。

好きなときに何回でもプレイしてみてくださいね。
 
Thanks for playing - Sincerely, Willem Larsen

