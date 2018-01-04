---
layout: post
title: ! はじめに
short_title: ! はじめに
tags: preRubyKaigi2011 RubyKaigi2010Interviews
---


RubyKaigi2010 では gihyo.jp での [RubyKaigi2010 のレポート](http://gihyo.jp/news/report/01/rubykaigi2010)が日々更新されていましたが、実はそこには掲載されていない、開催終了後のインタビューがありました。KaigiFreaks レポート班と gihyo.jp 編集部が RubyKaigi2010 の運営委員長 (角谷さん) と運営委員長補佐 (島田さん) へインタビューした内容をるびまへ掲載します。お楽しみください。

## インタビュー

聞き手
:  gihyo.jp 編集部、[KaigiFreaks レポート班 (赤松祐希さん, 大和田純さん, すがわらまさのりさん, 白土慧さん, 三村益隆さん)](http://gihyo.jp/news/report/01/rubykaigi2010)

語り手
:  角谷さん、島田さん

日にち
:  2010 年 m 月 n 日  // FIXME

場所
:  の某所 // FIXME

### 目次

* Table of content
{:toc}


### RubyKaigi2010 の感想

__三村__ まずは RubyKaigi2010 が終わっての感想を率直に聞かせてください。140 文字程度でお願いします。

__角谷__ 会期が無事に終わった。まだ残務はあるけど、最後までつつがなく運営できて、若干片付けすぎたきらい[^1]はあるけれど、なんとか撤収までやれたなあ、というのが率直な感想。

__島田__ 感想か……複雑な気分[^2]なのでまだよくわかんない。ただ、イベントとしては、RubyKaigi2007 の時に Dave Thomas から出された宿題にイベント全体で答えを出せた気がします。

#### Dave Thomas からの宿題

__――__ Dave Thomas から出された宿題とは？

__島田__ [RubyKaigi2007 のときに Dave Thomas が基調講演で言っていた](http://jp.rubyist.net/RubyKaigi2007/Log0610-S5.html)ことがあって、「新しい人たちがコミュニティに来るから、そこで断絶してしまうのではなく、ちゃんと迎え入れて、かつ Ruby らしいやりかたで包んで、新しい人も古い人もやっていけるような道を探しなさい」と。これを宿題だと受け止めていました。

__角谷__ 補足すると、「今までは Ruby のコミュニティは Ruby が好きな人たちだけで集まって仲良く暮らしていた。それで幸せになれた人たちがいる (まあ、僕ら[^3]もそういう人たちの一人だと思っていい) 。でも 2007 年以降、Ruby のコミュニティもどんどん大きくなっていく。そうすると、これまでとは違った、色んな人が来るようになる。そのときに、僕らはどうすればいいのか。」というのが Dave の問いかけだった。そして「新しく来た人たちに僕らのやり方を見せて、彼らを迎え入れなきゃならない。その準備をしろ。」と。

__角谷__ Dave が言ったことはお話としてはわかるんですね。でも、具体的に僕らは何をどうすればいいのかなあ、というのが見えなかった。だからそれを宿題だと受け止めて、毎年そのことも考えながら、だんだん大きくなっていく RubyKaigi を運営していた。2008、2009 と少しずつ色々なものを積み重ねていって、2010 で一つの形になったかなあ、という気がしている。そういう意味では Dave の宿題を片付けられたといえるかもしれない。

__島田__ といっても、会期中はそんな気は全然しなかったんだけど、RubyKaigi2010 が終わって 1 週間ぐらい経ってみると「宿題を片付けられたのかもしれないなあ」ってだんだん思えるようになってきた。

#### Conflicts and Resolutions

__角谷__ カンファレンスとしては結果的にテーマともうまいこと合ってましたね。「[Conflicts and Resolutions](http://rubykaigi.org/2010/ja/Prospectus)」。色々な衝突と色々な解決があって。[井上さんが RubyKaigi 2010 の後に御自身のブログにまとめてくれてた](http://blog.new-bamboo.co.uk/2010/9/14/ruby-divide-at-rubykaigi-2010-and-what-can-you-do-as-a-rubyist-part-1)けど、あんなに色んな軸があったとは事前に思ってなかったなあ。「英語と日本語」「ホビーとビジネス」「 before Rails と Post Rails 」。色んな衝突の軸があったんだなあ、と感心した。

__角谷__ ひょっとしたら実行委員長の高橋さんはこうした軸も事前に考えていたかもしれないけど、運営チームではそんなに突っ込んで話はしてこなかったし。「色々とバラバラになっていきそうな感じはするよね」程度の空気は共有していたと思いますが、CFP (Call for Presentation) に応募してきた個別の発表それぞれが、テーマに沿うことを最重要視していたわけでもないし、選考する実行委員の側も、選考にあたってはさほど重視していない。

__大和田__ 運営 ML でもあんまりそういう話してませんでしたよね。

__角谷__ うん、運営と準備のことで頭がいっぱいだもんねえ。

__大和田__ [gihyo.jp](http://gihyo.jp/news/report/01/rubykaigi2010) の当日レポートを読んでると「テーマに沿った内容でした」というような感想がいくつかあったと思うんですけど、当日レポート班の人は何かテーマを強く意識することってありました？

__三村__ テーマについて紹介を書いた直前レポートぐらいですね。

__大和田__ 文章書かなきゃいけないときに、うまくテーマに絡めて書けたら書く。そういう取っ掛かりがなかったらそんなに意識しないかも。

__赤松__ 毎年の RubyKaigi のテーマってどういう風に決まるんですか？

__角谷__ 私が「来年この日に RubyKaigi をやろうと思ったら、この日に開催趣意書がないとマズい」という段取りで設定した締切日に、高橋さんがポーンと出してくるんですよ。毎年。

__大和田__ ポーンとあれが出せるのはすごい。

__角谷__ 毎年、高橋さんが開催趣意書とテーマをポーンと出してきたら RubyKaigi のプロジェクトが始まるんですよ。運営チームの私としては、そのテーマをどれだけうまく実装できるかがミッションになる。テーマが乗っかる器をうまく準備できるかどうかの勝負。

__大和田__ 個人的には RubyKaigi 2009 の方が Conflicts の話が多かった気がしました。 2010 は Resolution の話のが多かったような気がします。Conflicts and Resolution と、テーマに Resolution まで含めているからかもしれませんが、衝突してるだけじゃないよねって話が多かった印象が残ってます。 2009 は色々衝突があるってだけで終わっていた。たとえば Web アプリケーションフレームワークでいえば、Rails も Merb もあるし、 Ramaze の作者が一般参加者としてシレっと参加していたり。ところが、2010 では Rails3 でどこも丸く収まった感じで。「私たち結婚することになりました」みたいな。

#### RubyKaigi の外だったものへ歩み寄る

__島田__ 2009 から伸ばしたところでいうと、iRubyKaigi[^4]がある。2009 は参加者の方から勝手にやってもらえたけど、実行委員側が歩み寄ったらどうなるかなっていったらああなって。結果、Android版もできたりとかすごいうまくいった。企画とかとおなじくらいうまくいったんじゃないかなと思っている。

__角谷__ 2009 のときに iRubyKaigi を伊藤さんが勝手につくっていてですね……「そんな便利なもの作るんだったら喜んで協力したいから声かけてくれよ！」という思いがあって。そこで「ぼくらになんか足りなかったところありませんか？」というやりとりをして、それを踏まえて rubykaigi.org を実装した。

__島田__ 2010 はたとえば「運営側からどういうデータ欲しいですか」という声かけをしたりするようになりました。

__角谷__ そうして、正式にやってくれるようになった。Apple Store に申請してくれてみんなダウンロードできるようになった。そうしたら、たださんが Apple 製品を触るくらいの衝撃[^5]があった。で、そしたら Android 版をポーンと [takkaw](http://twitter.com/#!/takkaw) がつくってくれて。

__島田__ これまではいち参加者だった人が、もう一歩進んで Contribution できるようなことを、2010 はいろんなところで増やしました。個人スポンサーという形で Contribution の受け皿を用意したり、企画という形で発表の形にとらわれない RubyKaigi への参加の形を作ってみたりしました。

__角谷__ スポンサーについては、スポンサーされることについて向き合ったということもあって。2009 までは「イベントってスポンサーとかいるよね」みたいな感じで何となくなっていた感があった。「イベントってスポンサーのブースとかあるよね。いっぺんやってみよっか」みたいな。それを続けていたら、2009 のスポンサーブースのやり方はあまり良くなかった。スポンサーにも参加者にも発表者にもあまり益がなかった。だから考えなおして、RubyKaigi のスポンサーってなんだ、みたいな話をしました。で、その答えのひとつとして「スポンサー企業の担当者とちゃんと話をできてないよね」というのがあって。結局、全部のスポンサー企業さんときちんとお話はできなかったんですが、例えば Ricoh さんは 2008 から支援いただいてるのに、あんまりコミュニケーションを取れてなかった。 Ricoh さんが 3 年間も続けてスポンサーしてくれているのどういう思いからなのか、とか。で、話をしにいって、お互いどういうことができたら嬉しいのか、という話を。歩み寄りというと語弊があるかもしれませんが、実行委員とスポンサーという形だけじゃなくて、一緒に何ができるかな、という話をした。

__島田__ Ricoh さんはたとえば壁紙ダウンロードとかっていう、ブースじゃない Ricoh さんなりのやり方でやるし、Cookpad さんは Cookpad さんらしいイベントをやるしとか、みんな自分たちらしいやり方で、Contribution をしてくれた。

__角谷__ 2010 からスポンサーセッションをなくしたのもそうした議論の結果です。

__――__ スポンサーセッションなくしたしブースもなくしたしで、スポンサーさんにとっては何が参加するモチベーションだったんでしょう。

__角谷__ それは企業さんによりけりですよ。話を聞いてもらいたいという企業さんは「じゃあ CFP 出してください」、企画出したいなら「企画に応募してください」と。

__島田__ 企業のかたも、他の参加者と同じ土俵でコンテンツを競いましょう、と。スポンサーセッションという優遇枠じゃなくて、発表したいなら本気で他の Rubyist たちに負けないレベルの発表をしてください、と。

__――__ 落とすかもしれませんよ、と。

__角谷__ もちろん。

__島田__ お互い本気でやりましょうというメッセージにしたかった。

__角谷__ スポンサー企業さんも、コンテンツについては RubyKaigi に来る参加者にとってなにが嬉しいのかを一緒に考えてみましょう、と。まあ、ぜんぶきちんとやれたかというとむずかしいですけど。 2009 のよくなかったところを、自分たちにとってどういうことなんだろうねというのを考えなおした、という観点からは結果を出せたと思う。

#### 海外との関わり方

__大和田__ 2009 では最初に「海外をがんばる」というのがあって、 2010 は全体で言うと 2009 でやったことをもっとしっかりやったぞと。海外の発表者や参加者に対して、さらに上の試みとか取り組みというのはあったんですか？

__角谷__ アナウンスとかをなるべく英語も一緒に出すようにしたり、海外参加者の Overseas のメーリングリストとか―― 2009 も作ったけどあんまり活用できていなかったので、作って放置じゃなくて「入ってください」とか「こういう人が来てるんですけど」というのを、 2009 よりも英語で情報を出せるようにした。セッション概要もなるべく英語をくださいというのをお願いした。

__島田__ CFP も基本が英語だった

__角谷__ 優遇し過ぎなんじゃないの、日本でやるのにそこまで英語とかやらなくてもいいんじゃないの、という意見も見たけど、どう言えばいいんだろうね。「日本語だけど Ruby の話をやってんだし」と。日本語だというだけでスルーされるにはもったいないっていう気持ちはあって、海外から来てる人たちに「こういうことやってるんだな」っていうくらいは伝わるようにしたいという思いはあった。「来ていいよ」っていうだけじゃなくて、事前に「RubyKaigi というイベントがあって、こういうことをします」みたいなのをもう少し伝えたいなという。きちんとやるということの中身はそんなかんじ。興味を持った人にもっと伝わるようにしたい。オーストラリアの人たちはすごく喜んでくれて、嬉しいです。

__角谷__ そういう意味で言うと、日本に住んでる Non-Japanese のひとたちに RubyKaigi が届いた感触はすごくあったので、結果的にやってよかった。日本にいるけど「外人」というので別れちゃっている。英語の情報を日本にいても取っていて、日本語の情報はない。日本にいながら、いわゆる Ruby のもっと大きいコミュニティにつながっているようなひとたち。そういう人たちとお互いに見えるようになった。Tokyo Ruby Meetup みたいなのもできたりとか。Yokohama.rb で 2007 に話してくれたジョンメトローさんが日本の Rubyist のことをサポートしてくれてる、陰ながら。彼もシャイな Rubyist なので自分から「オレがオレが」って感じじゃないんだけど、海外の Rubyist の日本の Rubyist に対する見当違いなコメントをフォローアップしてくれたりだとか、Yokohama.rb とかも手伝ってやってくれたりだとか。RubyKaigi にまつわる tweet をそっと RT してくれたりとか、とても助けてもらってます。

__大和田__ シャイな感じで。

__角谷__ 海外へ届ける、というのを手伝ってくれる人は日本にもいるんですよ。日本に住んでるガイジンで。レオなんかも――日本語が流暢になりすぎてときどき忘れるけど、彼もガイジンなので。そういう人たちといままでよりももう少し広くつながるきっかけができたのは成果なんじゃないかな。海外に向けてというわけじゃなくて。ランゲージバリアの話になっちゃうけど、日本だからといって日本人ばっかりでもないっていう。まあ、やれる範囲でいいのでやれるとこまででいいんですけど。お互いやれる範囲でうまいことやれるといいなあと思っています。

#### 企画部屋

__――__ 企画部屋の話。私が思ったのは企画部屋が増えて、2009 は RegionalRubyKaigi についての話をする会議とか tDiary 会議とかそういう運営に近い人がやってますという企画が中心だったんですけど、2010 は参加者が立ち上げる企画中心になったように見えて

__島田__ 元々そうですよ。参加者がやるものとして企画を始めて、2010 ではもっとしっかりやった。

__――__ それで結構、繋るんですけど、参加者がやっぱり見たいものが増えて、見たいと言ったらちょっと受動的なんですけど、人が増えた結果うまいこと今回 RubyKaigi が 2009 より良かったんじゃないかって。笑顔が多かったねっていうのが今一把握できていなかったんですけど。

__角谷__ 人っていうのは参加者がってことですか？

__――__ 1 人の参加者が結局大ホール、2 トラック内で

__角谷__ 本編として結果的にたくさんになってるので色んな興味関心に対して答えられるようになってるから満足度があがってるんじゃないか

__――__ っていう風に私は感じたんですけど。そういう効果もあったんじゃないかな。

__島田__ 参加できるところがあった。

__――__ で、「Kaigi」もできてるから、自分が発言する、自分から発言できてたかどうかは、私は企画部屋行ってないのでわからないですけど、そういうのが増えたんで、なんて言うんですかね。だから、参加者がよりRubyKaigiにコミット出来たっていうか、じゃないのかなって。

__角谷__ ただ行って帰ってきただけじゃない体験が出来たんじゃないかってことですよね。

__――__ そうですね。自分の本当に興味のあるものが聞けたんじゃないかなって思ったりするんですけど。それに関してどう思います？って漠然としるぎると思うんですけど。

__角谷__ いえいえ、えっと。そういう意味だと、さっき話した 2009 で良かったことをもっとやってみようっていうのが延長線で。 2010 は本当に借りたけど使いにくい部屋があったんでなんかまぁ、来た人が使いたかったら使えばいいんじゃないっていうのを、もう本当に現場でやったら、こんなのやってたのっていうフィードバックをもらって。まぁやった人達は結構楽しそうだったね、じゃあそれをもっと実行委員としてもっとちゃんとサポートして形にしようかっていうぐらいなんですよ。あんまりその、それで人をいっぱい、まぁ部屋もあるからいいんじゃない、みたいな。あと全部借りたら、廊下も使えるっていうそういうオペレーションの理由もあってボーンと取った。で、何を入れたらいいからわからないから「だして」みたいな。セッションはrejectしてるんですね、結構。

__角谷__ セッションは結構rejectしているけど、企画は基本的になんらかの形でとりこんでいて、落としたやつはない。やりたいって言ったやつは全部やらした。なんらかの形でとにかくいれた形にしましたね。

__島田__ もっとこじんまりとしちゃうかなぁと心配していたんだけど、全部どの企画も人が入って、なんか良かったなぁと。 で、企画がやっていない時間でも、あそこ使ってなんか話している人もいたし、すごいよかった。

__角谷__ まぁ、 2010 の会場の雰囲気とかよりも、結構セッション中も、ほら 2009 も聞かないでなんかやっている人達が増えてきたので、そうするとなんか来ている人同士でなんかやれるんじゃないかっていうのはあったんですね。それで大きくした感じで、あんなに、

__――__ 盛況というか？

__角谷__ うん。あんなにみんな集っていろいろ話しをしたりとか

__島田__ 2009だと、その充電スペース、、その海外の人だとだいたい話聞かないで、そこで話ているっていうから給電所みたいなのを作って、そうしたらそこにすごい人が集って、企画はあったんだけど、やっぱ給電所はもう知っている人達しかうまく話せないけど、企画部屋みたいなのはなんか、話題があって参加する形だから、そんなにまわりに知らない人がいてもよくて、それでドアが開いていて、外でなんとなく見ていても「ここ入れそうだな。」と思ったら入ったり。

__――__ 入って行きやすい感じで？

__角谷__ そうですね。ドアは閉めないって運用にしたんで。

__島田__ もともとコミニュティにちっちゃいコミニュティに属していない人でも入っていけるように結果的になったので、 2009 よりも全然だから、 2009 は企画も給電所も知ったコミュニティの人が集って話す場でしかなかったのが、 2010 はそうじゃない人達がはいっていけるようになったので

__角谷__ RubyKaigiっていう1つのイベントで、いろんなところから人が集って、せっかく人が集っているんだから、せっかくなんだから「いろいろHackしないか？」とか「いろいろ話したりしないか？」みたいなのが去年の形だった。今年はそれをもっと強くしたら、そこにそれを知ってきたわけじゃない人がプラっと来てというのがなんか面白そうだからやってみました。でなんか、「聞きたいセッションあるから抜けま〜す。」とかみたいな感じのこと。

__島田__ 逆に、「あのセッション聞きたかったのに、これ楽しかったから終わっちゃってた。」

一同：(笑い)

__――__ うれしい誤算みたいな？

__島田__ みたいな話も聞けたのは良かった。「こっち聞きたいのに抜けれない。」みたいな。

__全員__ (笑)

__大和田__ すごい、潜在的にそういった体験が需要があった解釈？

__角谷、島田__ わからないねぇ。

__角谷__ だって、ほっといたらするかっていうと、たぶん無い。だから、なんていうか、なんでそれができているのかよくわからない。いわゆるRubyとか好きな人とか、そんな

__大和田__ シャイな？

__角谷__ そう、シャイな人も多い (笑)

__島田__ 企画もそう割りと Ruby の企画だけど、Ruby じゃない話も多かったじゃないですか。

__角谷__ うん。

__島田__ たとえば vim とか、わりと入っていきやすいのがよかったのかなぁ。「海外で暮らす Rubyist だけど何か聞きたいことある？」とか、cookpad とか

__角谷__ インセント(？)トピックス的なやつだったからなのかなぁ。わかんないな。

__島田__ でも、わりと口を挟める、なんか言いたい人が多そうじゃないですかw。どうなの？とかw。というのがよかったんじゃないのかなぁ。

__大和田__ ていうと、今のその需要があるっていうことの質問の次は、 2011では企画って、やっぱどうなりそうですかっていうのが。

__角谷__ やるんじゃない？どうやるかは、わかんない。

__大和田__ 2010 は会場がよかったですよね。企画部屋が、こっちはなんか盛り上っているぞとかが、並んでて見える、あれがなんか階段昇って下でとかだとちょっと違うのかなぁっていうのが

__島田__ そこでやれるRubyKaigiは、ちゃんとあるんだよ。

__大和田__ うんうん。

__島田__ 2010 は、ああいう場所でやれたからああなっただけで、あの場所じゃなきゃできなかったっていうわけじゃない。

#### 個人スポンサー

__三村__ 2010 は新たな挑戦として、個人スポンサーってやったじゃないですか。あれはターゲットとかを考えたのかなぁと

__角谷__ いや、実験ですよ。

__赤松__ 来るかなぁぐらい？

__角谷__ 料金の話って、ずっと出てたんですね。安すぎるとか、もっと高くして、例えば外部の業者とかつかって、もっと運営の人たちが(楽をする)という話もあったりして。基本的にだんだん大きくするという中でやっているので、あんまり大きく変えることができないんだけど。チケットの販売用に paypal を使って、インフラができたり、だいたいpaypalのやり方もわかったりしたので、集めてみたらどうなるだろうとか。

__角谷__ 会場代が大きくなるのでかかるんだけど、経済情勢的にあんまりお金をだしてもらえる状態じゃないし、スポンサー増やしてスポンサーのメリットをってやっていければ、大事なことなんだけど、そればっかりになっちゃ本末転倒じゃないかなぁと

__島田__ それとチケット代は高くしないで、高橋さんのビジョンとしての誰でも来れるRubyKaigiっていうのがあるから、その隙間を埋めるにはどういったやり方があるかなぁって。じゃあ、だしたい人にだしたい額だしてもらえればいいんじゃない。どれだけ集まるかわからないけど。

__角谷__ 例えば、特別な特典はなくて、名前だけ、おまつりだから、お祭りのときってあるじゃん、 提灯とか札とか。ああいうノリでやったら、みんなにどれぐらいだしてもらえるんだろうねぇっていう感じの実験。

__――__ 何人ぐらいあつまったんですか？

__角谷__ 70人ぐらい。正確に数えていないんですが、100人はいかないかんじ。いろんな人がいましたねぇ。あの純粋にスポンサーっていうわけじゃなくて、企業スポンサーやっていてだしてくれた人もいるし、スピーカーの人もいるし、Rubyのコミッターの人でだしてくれた人もいるし。海外の人とかでだしてくれた人もいるし。ほんとにいろんな人がだしてくれました。ありがたいことです。あたらしい取り組みでした。

__三村__ そういった意味だと成功した？

__角谷__ 一番上のランクのゴールドスポンサーの企業から出してもらったお金よりもたくさん集まった。RubyKaigi の一番大口のスポンサーは個人スポンサーのみなさん。いい話でしょ。すごくすてき。スポンサーも入るけど、来る人たちで支えるかたちになった。いいかたちにできた。

### ボランティアのイベントをどう続けていくか

#### 終わってみるべき

__三村__ 2009 で卜部さん[^6]のアレがあって。

__角谷__ [終わってみるべき](http://shyouhei.tumblr.com/post/145555071/ruby)。

__三村__ あれがあって意識したこととかはあったりしたんですか？　卜部さんのなんだろう。運営が辛そうとか、スタッフが辛そうだとか言われてやり方を変えたとか。そういうのは。

__島田__ なんか意識しましたっけ。

__角谷__ うん。なんだろ、終わってみるべきって言われちゃうようなやり方はやめたいなぁとか。もうちょっと次の所に行きたいなぁっていう。意識して。

__――__ スタッフ数ってどうなんでしたっけ、 2010 は。

__角谷__ すごい増えてます。一番多いと思う。50 人ぐらいいるんじゃないか。あんまり数えてないけど。40 後半とか。はぐれスタッフみたいな人もいるから。カウントの仕方が難しいんだけど。

__角谷__ オペレーションというか段取りってイベントの準備なんですよ。誰かが絶対この人じゃないとダメだっていう物でもないと思っていて

__角谷__ 今までやってきた RubyKaigi は基本的には誰がはじめるのかっていうと、高橋さんがはじめるんです。他の人には中々変えがたい。やり方は色々あると思うんですけど、RubyKaigi はそういうやり方。高橋さんがやる、来年はこれでやります、こういうテーマでやります、っていうのからどういう風にやりたいのかどれぐらい入れたいのか、あとは実務の問題で、会場はこのぐらいの大きさでとか。

__角谷__ こういう RubyKaigi にしたいっていうのはささださんで。プログラムに関しては最終的にはささださんが決める

__角谷__ 運営はまぁ、この人じゃないとってあるのもおかしいなぁってのがあったんで、誰か一緒にやってくれないかなぁと見回して、お願いしました。というかんじ

#### 増えたスタッフの中のギャップを埋める

__角谷__ ボランティアのイベントをどう続けていくかって言った時に、すごく訓練をされた少数の人達でコミットメントしてやるっていうやり方で、スケールするのかっていうと難しいんじゃないか。色んな人を巻きこんでその人が丸抱えしないようにして行くようなやり方しかないんじゃないっていう話を島田さんとちょっと前にした。「終わってみるべき」とか「燃えつきちゃうんじゃないか」のに対して。

__角谷__ それで 2010 は今まではコアに近い人達が一人でいくつも重ねて持ってた仕事に名前を付けて分けて、別の人にやってもらってっていう風にしたんだけど。コミニュケーションデザインとか、受付を Team Welcome とか、KaigiFreaks も分けて、とか。

__角谷__ で、それを増やすとコミュニケートしないといけないよねっていうのと、あと、少数だと抱えてもいいっていうか、直前に終わりましたって言えればいいんだけど、チームが分かれたりするとそうも言ってられないと。そうすると、わからないと思ってることとか相手に伝わらないので、良い状況なのか良くない状況なのかわからないので、取り急ぎ、dump しますっていうのをやっていた。決まってないし、どうしたらいいかわからないんだけど、なんかこんな気がするみたいなのを ML にポストする。すぐどうなるということはないけど、まず状況を出す。見せて、状況は作業の進捗とかじゃなくて気分とか気持ちとか心配していることを。ぼんやりした心配ごととかを。不安とかを。そういうのを片付けていく。

__島田__ で、そういう詳細を、自分が抱えているけど出来ないっていうのを dump するときもあれば、あまりクリティカルなタスクはないからいつでもやれば出来るんだけど、誰かにやって欲しいなってことをお膳立てして「こういう仕事があってこういう風にやるんだけど誰かやりませんか？」っていう形にして運営 ML に投げるとかやっていた。拾ってもらえたら、ぼくがやってたことでも他の人も経験できるなぁとか考えて。

__島田__ 皆の中でギャップがあるところをコミュニケーションで埋めていかなければいけないっていうのをぼくは割と意識的にメールを書いていたので長くなったり、メールの流量も増えて。

__角谷__ 運営 ML が爆発するってのは名物みたいになってる

__大和田__ まぁ名物ですねぇ

__角谷__ 2010 は 5,500 ぐらいで

### バラしたタスクを全部集めても RubyKaigi じゃない

#### 毎年 ITS の運用に失敗している

__大和田__ 会期中のスタッフ弁当の手配について「毎年なんでこうなるんだ」って角谷さんが言っていて。スタッフ弁当の手配が開催の直前までなかなか片付かない。

__角谷__ 弁当って多分、一番おもしろくないんですよ。難しいわりには。例えば食べ物だからいくつ頼むとか、いくらぐらいお金がかかるとか考えなきゃいけないことはいっぱいあるんだけど、あまり達成感がない。会場に届いたものを配って終わりだから。あまり人気がない。だから弁当の手配に手を挙げるスタッフがなかなかいないのもわかる。だからやらなくてもいいんだけど、運営的には。

__角谷__ 1人の人が持てる心配ごとの量には上限があるので、なんか簡単なタスクとかやればいいんだよってやつでも、上限を超えちゃうとなんか1個1個ちゃんと出来なくなっちゃうのね。そうするとつまらなくてもいいから1個でもいいかスタッフ同士でわかちあうように出来ないかなぁ。誰かやりませんかっていうのを。

__島田__ RubyKaigi は毎年 ITS を運用するのに失敗していて。最近角谷さんがよくタスクを、例えばお弁当もお弁当係とかお弁当を頼むってタスクを登録するのは簡単なんだけど、登録するだけじゃどうしようもない。誰か一緒にやってくる人をみつけるにはコミニュケーションを始めないといけないんだけど、ITSとかは登録したところで心配してる人はなんか投げ出した気持ちになるし、他の人達は別にそんなの興味ないからって言ってやらないから ITS は全然よくない。

__大和田__ 弁当の手配がチケットに登録してあって、じゃあそれを誰かが「自分がやります」って言うかっていうとおぼつかない。

__島田__ スタッフML上で細かいコミニュケーションややり取りを重ねて行かないと、庶務の仕事が出来ない。

__大和田__ 毎週、ML上で弁当どうなってますか、どうなってますかって言っても仕方なくて、弁当はこれはこれで大事で、弁当は弁当なりに意義はあるんですよみたいなところから話をしないといけない。

__島田__ 2010 ではそういう細かいやり取りをするようにした。 2009 までは ITS に登録してたださんがMLでどうなってますかー？って聞くとか。そうやっていたのを 2010 ではML上でちゃんとコミニュケーションして誰かに拾ってもらうようにしたから、MLの流量がかなり増えてしまった。

__白土__ 2009 の時はなんかそういうシステムを使ってってやってたんですか？

__角谷__ Remember The Milk。

__島田__ Redmine じゃないですか？ 2008 が RTM で、2009 は Redmine。でも、Redmineはいつも途中でうまく使えなくなっちゃう。

__角谷__ Redmine はいつも使い切れたことがない。

#### やる事とやる事の間をどう繋ぐか

__角谷__ RubyKaigi はイベントだから、終わりが決まってて基本的にはWBSで分解できるはずだって仮説を持たせてみて、もっときっちりやる事と成果物を決めてやった方がいいんじゃないか、ってのをやってみたんだけどそうやっても RubyKaigi は出来ないんだよ。それだけじゃわからないのね。現場の3日間の感じにならない。バラしたタスクを全部集めても RubyKaigi じゃないんですよ。

__大和田__ なんかタスクのリストだけあっても、全然場を表してないというか。

__角谷__ RubyKaigi っていうイベントをタスクに切り刻んでも RubyKaigi にならない。なんかうまく言えないけどね。やる事とやる事の間をどう繋ぐかとか、そこにスタッフとして関わることで、どういう結果というかなんか、いやおもしろいよみたいな。外部の人とやり取りが出来ますよーみたいな事をとか、そこを重ねていったらなんか RubyKaigi になる。

__大和田__ 今書いているるびまの [RubyKaigi の裏側](http://jp.rubyist.net/magazine/?0031-RubyKaigi2010)の記事がそういう形になってて、だから読んでて楽しいのかな。各スタッフ班の作業を箇条書きとかで書くんじゃなくて、大変なこととか楽しいこととかも丁書いてあって、それがよく出来てるなぁって。レポート班のところは赤松さんが書いてくれてて、他の班のを読んだスタッフの人達が自分たちの班も書きましたってのが増えてきてて。

__角谷__ 基本的に感情を処理する。していることが多かった。この1年間。

### 最後の RubyKaigi

#### RubyKaigi2011 の構想

__三村__ 2011年は、現時点でこうしていこうって考えているのがある？

__角谷__ ない (キリッ

__三村__ なんもまだ、はじまってない？

__角谷__ 2011は、今のところ白紙。

__白土__ 白紙!!

__角谷__ 最後っていうテーマだけは決まっている。

__白土__ 角谷さんが、RubyKaigi 終わる宣言、つまりはっきりと RubyKaigi が終わるって聞いたのは、高橋さんのクロージングの時が初めてなんですか？

__角谷__ どうなんだっけ？

__島田__ いや、ふつうにオペレーションメールに流れていた。

__白土__ 話題としては事前からそういう話はありましたよね。実行委員の分科会のときにぼくは知ったので。

__島田__ 普通にメーリングリストにながれてた。

__角谷__ 分科会の前に話はでた。今の RubyKaigi の枠組みで都内でやろうと思うと会場を用意するのにその抽選が一年前だったりとかで、あの規模を都内でやろうと思うと一年前から動かないといけなくい。 2010 はいろいろバタバタして準備が遅れた。時期も 8 月終わりになっちゃって、場所も筑波になっちゃったというのもあったので、2011 は東京でやりたいねって。 そうすると一年前に準備しなきゃってなるので、大体7月前後に「2011年の7月どうしましょうか？」って話をしてて。その話のなかで高橋さんの方から「いやぁ、一回終わってみるべきじゃないですかぁ」みたいなことは言っていたんです。

#### 「最終回だから最終回です」

__角谷__ RubyKaigi はずっと拡大路線でやってきてたんですね。

__大和田__ もっと来たい人がこれるようにね

__角谷__ とは言っても、RubyKaigi の規模はどんどん大きくなってるし、今の枠組みでこれ以上大きくしていく限界だなぁっていう話もあって。そこで一回終わってみるべきかなぁという気持ちぐらいの感じでした。lクロージングのあんなハッキリとした感じではなくて。

__白土__ それは RubyKaigi の高橋さんの宣言の前までは可能性としての話だった？

__角谷__ RubyKaigi は 2006 を0回目とすればいいかな。2006 っていうのはほんとに何もわからず全部手探りでとにかくやったていう0回目。で、2006 が一回終わって、来年やるの？やるとしたらどうやるの？みたいな話をダイビルで、ささださんと高橋さんたちとけっこう議論をしたんです。で、やるっていう話になって、今の実行委員長、プログラム委員長、運営委員長っていう三役体制になった。で、RubyKaigi は 2007 からはじまったので、さっきもでたDaveTomasの話が、そう意味だと、1回目に、RubyKaigiってまたやろうってなったときの頭にきたのが、DaveTomasのキーノートだったんですね。それが2007に、あの運営にかかわった人にとってそれがおおっきいのが、わかんない。それが島田さんとか、そのとき初めてだったからわかんないけど

__島田__ ぼくは、当日スタッフでそのとき初めてはいって

__角谷__ あれがほんとうの始まりというか、2007 の最後にDaveが残していった"なんか"だったの。当時はよくわかんなかった。そのなにかをどうしたらいいんだろうなぁっていう、あれを宿題だと思ってやってたんですよ。で、筑波で 2008 をやって、RubyConf やっている人たちに来てほしいっていうのがあって、Chadに声をかけた。2007 も声をかけたのかな、その時は都合があわなくて来てもらえなくったけど、2008 は来てくれて。でも、なにかを発表するのはやらなくてもいいって、 2010 の基調講演の最初で Chad が言っていたと思うんですけど、「この場で話すのが恐怖」って。「自分の恐怖と向きあうことなんだ」って。あのすごい Rubyist がいる、自分のヒーローたちの前でキーノートっていうのは、すごく怖かったんだっていう話をしてくれた。Chad が 2008 で来てくれて、意外に日本行けるねって思って、みんな来たらいいよって、Chadに海外から何人っていわれて、10人か20人かなぁって答えたら、来年は50だねって2008に言われたので、2009で、もっとインターナショナリズム、もっと海外の人に来てもらおうっていうのをもっとやってみた。というのをやってきた。それをじゃあ、この先どうするのって言ったときに、なんか一回チャラにしたいって。だから、終わり。で、RubyKaigi変わったよね？って言われたら、変わりましたからっていうことみたいだと。

__――__ それはRubyKaigi終わった後、twitterで高橋さんと角谷さんのやりとりで、「あれは額面通りうけとっていいんですか？なんかびっくりしました」みたいなやりとりがあったと思うんですけど。

__角谷__ ありました。だから、それはそういう今迄やってきた RubyKaigi、いわゆる「愛と感動の RubyKaigi 」みたいなイメージとか、規模を大きくするとか、今のこういうボランティアベースの体制でやるっていう、2006に1回目やって7,8,9,10ってやってやってきたこの路線を一旦リセットしたいというので、終わりです。で、しれっと 2012 をやってみたりとか、たとえばホテルとか海外のカンファレンスみたいに 5 万円でやりますみたいなのもできるじゃないですか。別に終わりですって言われても、2012もあるねみたいな。変わったねっていわれて、今迄みたいなやり方みたいな大きいのじゃないかもしれない。値段も高いとか。RubyKaigi変わったね、変ったよみたいな。

__――__ 結局、あれなんですか？　そのとき高橋さんがいっていたのを角谷さんも違ったようにうけとめていて、それで額面通りになったのかなぁって

__角谷__ そうです。だから、2011 で終わりって言うけど、ぼくは 2012 もやるって、あるって思っていて。でも、やり方は今迄のは一回無くって、もっかい RubyKaigi って何だろうねっていう今 RubyKaigi やるとしたら、この状況の中で、もっかい最初の RubyKaigi やるとしたらどういうのを、誰が何をどうやるのというのを。たぶん実行委員長も高橋さんやるの？とか、そういうのを含めて、もっかい考える。で、2012 をやるって思ってた。となると、都内でやると 1 年前ぐらいにとらないといけないから、2011 が、はじまるより前に場所を来年どれぐらいの規模でやって、どうふうにやりますよっていう話をしないと場所とれないので。そういう、 2010 やったような、みんなは 2010 のRubyKaigi、場所をどうするっていう話をしながら、次のRubyKaigiの準備をするんですね。それをやるんだと思ってた。でも、次回以降は無いですって言うから、探さないですよみたいな。探さなくていいんですか？みたいな。えっ、ホント？みたいな。そんな話をロールプレイというか、最終回だとして、じゃあ次はどうするのかっていうのを、そういうロールプレイをするというのが次なんだと。これはこれで終わりだとして、次ぜんぜん違うのをやるとしたら、最後だからやり残したこととか、最後だとどうしたらいいかというのをいっしょうけんめい考えるという。それはそれとして、次の場所は探さなくちゃいけなくて、来年どうします？っていうのを高橋さんに聞きながやるっていう、今までやってたオペレーションの次の段取りの-1のダンドリみたいなのを初めるんだろうなぁって思っていたら、そういうプロレスなのかなぁって思ってたら。「額面通りうけとってください」って、 あの人ガチモヒカンっていうのをときどき忘れるんですよ。甘いマスクに、柔和なマスクに。高橋さん優しいからなぁってたてたら、ふつうにモヒカンだった。「最終回だから最終回です」みたいな。

__――__ だから、2012 は同じ時期に同じぐらいのキャパでやることはできないっていう？

__角谷__ このままだと難しいんじゃないですか？　体制とか仕組みとか全部かえないと難しいんじゃないですかねぇ。

__――__  ガチモヒカンだし

__角谷__ だから、そういう、ほんとに止めるんだぁみたいな。ただ、それがどれぐらいなのかは、ちょっとまだ、どれぐらいの度合いでやるのかは、もうちょっと高橋さんと話をしないとわかんない。まだ、ちょっと答えはでてない。どうするんでしょうね。

#### Final RubyKaigi

__三村__ といったかんじだと、2011 の規模感的なものは今のままスケールする？

__角谷__ 規模だけでいえばスケールする

__大和田__ 会場のキャパもおっきいし

__角谷__ 会場のキャパは今回と同じ。ホールは同じぐらいの大きさ。都内で。もっと来ようと思えばこれる。規模としては同じような。

__角谷__ 史上最大の規模 (笑) 毎年史上最大の規模で (笑)

__大和田__ 記事のテンプレみたいな (笑)

__角谷__ 来年も史上最大の規模みたいな

__三村__ そういった意味だと、まだテーマもおりてきてない？

__角谷__ いや、テーマは "Final RubyKaigi"

__――__ あ、あれがテーマか

__角谷__ "Final RubyKaigi" かっこいいなぁ (笑) 字面は気にいっている (笑)

### 高橋さんのリーダーシップ

__――__ 島田さんとしては、その高橋さんの終わりますっていうのは、どう受けとめられているんですか？

__島田__ あー終わるんだ、みたいな (笑)

__島田__ もともと、角谷さんと話しているというのは、高橋さんがやりたいっていうことをやれるかどうかで、次は高橋さんが最後のRubyKaigiをやりたいっていうんだからやるんじゃないっていう

__角谷__ あー、だからそういう意味だと従順な受託開発根性というか

__島田__ 下請け (笑)

__角谷__ お客様の要望に対して、それを越える価値を提供するのが、普通のRubyKaigi (笑)

__角谷__ でも実際それがないと、始められないんだよね。ぼくらは

__島田__ 高橋さんがやりたいことをどれだけやれるかっていうのが、ぼくらがやらなきゃいけないことだから

__角谷__ 別にそれがなんかその話だけ聞いていると、なんかそうなっている。「the 高橋」みたいなのがいて、ぼくらがこうなんか、上からきてこう粛々とやるというふうにとられると、違うんだけど

__角谷__ 高橋さんがこういうふうにやりたいんだっていうビジョンと思いっていうのがあるんだよ。その強さがすごくある。

__角谷__ でもそれを高橋さんのためだけにやっているんじゃなくて、話す人とかスポンサーとか、いろんな Ruby の動きを伝えようとしている人たちとか、RubyKaigi はコミュニティ全体の動きが見えるようになる場所だから、純粋に高橋さんのためだけにやっているわけじゃないんだけど

__角谷__ 高橋さんがやりたいっていうものを出してきて、運営は、それをやるのに必要な人がきたり、頼んで入ってもらうっていうのをどうやって達成するかっていうのが面白い

__大和田__ 2009 の話とか、高橋さんとかささださんにインタビューしにいったほうがいいんじゃないの？って言われて行ってないんですけど、今の話を聞くと高橋さんとか何を考えているんだろうなっていうのが、ものすごい興味がわきましたねぇ。どういうことになっているんだろうなぁ。運営のMLみてても高橋さんは本当に困ったときにでてくるとか、あれどうなったの？とか

__角谷__ ジョーカー！！

__大和田__ あんまり、これやりたいとか直接的文面とか口頭では見えてないところなので、ビジョンがあるかおもしろい。

__角谷__ Ruby World Conference で高橋さんへの質問で「コミュニティにかわわるときに何か気をつけていることがありますか？」みたいなのがあったんだけど、「ブレーキをかけないことに気をつけている」って言っていたのね。それをやるなっていうのはダメだって。いいぞもっとやれみたいな。

__大和田__ それはすごいなぁ。

__角谷__ だから、なんかいいんだよ。リーダーのあり方として僕は面白いと。ああいうリーダーシップは面白いんで。つい肩入れしてしまう。

__島田__ 高橋さんは、pull request[^7] してもらいやすいような課題設定とか、もっていき方を意識していますって。なんかこう確固たるものがあって、こうじゃなきゃだめだっていうよりは、入ってこられる余地を残す

__角谷__ 「こういうテーマだとしたら、どうします？　どうしてくれますか？」みたいなかんじなんだよ。それでゲームがはじまるんですよ

### RubyKaigi2011 への意気込み

__大和田__ 最後に、RubyKaigi2011 の意気込みを

__島田__ [札幌 Ruby 会議]({% post_url articles/0033/2011-04-05-0033-SapporoRubyKaigi03Report %})でお待ちしています。札幌 Ruby 会議なんですよぼくの頭の中は[^8]

__島田__ そういう意味で言うと、運営委員長をやりたいです

__全員__ おおー

__島田__ ていう覚悟を、札幌 Ruby 会議が終わるまでにしてきます[^9]

__角谷__ 自分としては、コミュニケーションをもっといろいろとっていきたいなとおもっていて、例えば参加するつもりの人だったり、CFP のいい書き方とか、スポンサーの人にもいままでこういうのでしたとか、RubyKaigi に関わる人にコンタクト、コミュニケーションを強くしていきたいなと思っています。始まる前の情報がギョッとするところとかもう少し丁寧にいろんな人とコミュニケーションとりたい。最後なので。課題をどうにかするんじゃなくてやりたいことを。

__大和田__ 発表も、という tweet をしてましたね

__角谷__ Timeless way of RubyKaigi、時を超えた RubyKaigi の道。今日したみたいな話を。どうなるかわかんないけど、終わりなんだとしたら、ぼくらが 5 年間やったことはなんだったのか、なにを考えたのか、途中の話はあるけどつまりこうなんだっていうのは聴いてもらいたいというのはあります。RubyKaigiってなんだったのかっていうのではないけど、なくなったあとも、"Timeless way" だから。たぶんそれは RubyKaigi っていうものに入ってたなんかなんだろうと。Rubyist、おまえらが集まって Ruby の話するのがあるんだとしたら、それの "Timeless way" があるんだと。それを教えてあげる (笑)

__角谷__ それを踏まえてみんなどうするかはまた別の話というか、材料にしてもらいたい！　聞いてください！

__三村__ 島田さんは現時点では発表したいとかそういう意志は？

__島田__ 最後の RubyKaigi なんだったら、Ruby 札幌としてなにかやりたいと思っている。Ruby 札幌としては RubyKaigi でなにもやってない。ていうのは、ぼくが RubyKaigi2007 に当日スタッフとして参加した動機が、その直前に Ruby 札幌っていうコミュニティを始めて、そういうコミュニティに属したことが一回もなかったし Ruby も始めたばっかりだったので、やりかたが全くわかんなかったから、「こういう所に参加すればわかるんじゃないかな」と思って始めて参加した東京のイベントが RubyKaigi2008 の当日スタッフだった。そこからやってきた結果が札幌でもフィードバックしてるしこっちではこっちで恩返ししてるし。おしまいなんだとしたら、札幌でやってきたことがこうだったんだよというのを札幌ではやってるんだけど、東京の RubyKaigi に来てくれたみなさんに、その結果こうでしたみたいなのを報告できるとうれしいなぁと思っています

__――__ とてもよいですね

__全員__ ありがとうございました

[^1]: 会場だったつくば国際会議場の要求を超えて、撤収作業をしてしまい手戻りをしてばたばたしたことを指している
[^2]: RubyKaigi 自体ではなく、RubyKaigi 実行委員のしまださんとしての出来に当時は複雑な思いがあった模様。運営委員長をやり終えた 2011 年はまた違った感想だったのでしょうか。
[^3]: 角谷さんや島田さん
[^4]: RubyKaigi のための iPhone アプリ
[^5]: tDiary のただただしさん。アンチ Apple で有名 (？) 。出典はたとえば twitter 。 http://twitter.com/#!/tdtds/status/75706000614760448
[^6]: その卜部さんも RubyKaigi2012 は実行委員
[^7]: github で fork したブランチからパッチを取り込んでほしいときに送るリクエスト。ここでは行動を伴った提案の比喩
[^8]: インタビュー当時、RubyKaigi2010 に続いて札幌 Ruby 会議 03 が予定されていました。
[^9]: 当時は札幌 Ruby 会議で頭がいっぱいだけど、札幌が終われば今度は RubyKaigi2011 が島田さんの中で始まるということですね