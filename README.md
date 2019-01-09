# 防災設備における固有名詞の命名ルール検討-神奈川県大和市を例として-

## はじめに


　本研究は、神奈川県大和市内における全防火水槽とスタンドパイプに固有名詞を定義することを目的として、その設置状況基礎データとなるストリートビュー撮影を試みた。なぜこの研究を行うことになったのか。私の所属する空間情報学を専攻する古橋ゼミでは、専門とするドローンを使用して以前から防災活動に取り組んでいる。先生のコネクションもあり、防災に力を入れている大和市消防本部と連携したDRONE BIRDの活動をいくつか行ってきた。活動していく中で、大和市消防本部の藤田さんから、市内の防火水槽、スタンドパイプの認知度の低さに課題を抱えているとおっしゃっていた。これを解決するためにまずはそれらが認識されるよう一意の地域に根づいた固有名詞表現命名規則を作るため、位置情報と周辺情報を取得した。そしてそれに基づいてそれぞれが認識されやすいように固有名詞の命名ルール化を検討するというのが今回の目的であり、テーマ決定までの流れだ。今回は命名ルールを検討するまでに必要となる情報収集としてストリートビュー撮影を行った。そこから得た撮影方法と考察を述べていこうと思う。

　問題は、私はゼミ生であるがストリートビュー撮影の経験がなく、大和市民ではないし、市内に足を踏み入れたこともない、というところだ。撮影の方法もわからなければ、大和市に関しても無知なのである。そこで、今回はストリートビュー撮影に必要となる下準備から撮影方法まで、根底の知識として必要となる大和市の防災状況について、加えてデータのアップロード方法についてを第1章、第2章で今回の研究結果、第3章では考察として、結果に基づいて固有名詞の命名ルールを検討していこうと思う。


## 1. 大和市の防災状況と撮影準備、方法を含む研究内容

### 1-1. 撮影準備


　まずは前提として、研究を行う前に先生からいただいた言葉がある。今回のようなフィールドワークにおいては特に、”事前準備が非常に大切”ということだ。とりあえずやってみよう精神では成り立たないのである。フィールドワークには時期や時間が限られる。今回の場合はある程度の景色が一望できる晴天で、日が昇っている間のみだ。更に、ひたすらに自転車を漕ぎ続けるため、耐えられるほどのコンディションも必要不可欠なのである。ただでさえ締め切りが迫る中で、撮影ができるのはごく限られた時間のみであった。万全の下準備で望んでも、現場にはトラブルがつきもので、必ずと言っていいほど予期せぬ事件が起きる。そこまでを予想し、頭を働かせて対処できる準備を完璧に行わないと、フィールドワークはできないのである。

　前提が長くなったが、撮影に必要な下準備について述べていく。今回の撮影で使用するのは、360度パノラマカメラRICOH THETA Sで、これを専用のスタンドに付け、自転車にテープでしっかりと固定する。このスタンドは3段階伸ばすことができるが、今回使用した自転車では3段階伸ばすとバランスが保てない。自分の力量で保てる程度までの高さを見極める必要があった。また、見知らぬ土地でルートを確認するのにiPhoneは必須だ。確認しながら走行するにはiPhoneを自転車に固定する機材も必要不可欠であった。勿論、今回の撮影時期は冬。長時間の自転車走行は想像を遥かに超える寒さだ。私は二度も風邪を引いてしまった。防寒対策は入念に行うべきであり、タッチパネル対応の手袋は必需品だ。

![img_4613](https://user-images.githubusercontent.com/33411765/50824249-6fd96700-1379-11e9-9aeb-af2ee78ea464.JPG)
　これは実際に私が撮影用のセッティングをした写真だ。


### 1-2. ルート作成

  撮影において重要な役割を担うルート作成について述べる。前提として、大和市の防火水槽とスタンドパイプの位置情報はヤマトSOSアプリに掲載されている。この情報をGoogle earth proの地図に落とし込み、防火水槽とスタンドパイプそれぞれ違うアイコンを配置する。Google earth pro上ではマーカーで線を引き、その線の距離やかかる時間なども表示されるが、最短ルートや徒歩でなく自転車で通れる道なのかを判断することが不可能なため、非効率的だと判断し今回は利用しなかった。地図上に防火水槽とスタンドパイプの位置情報が掲載されているこのデータをKML化し、PCのウェブプラウザ上でGoogle mapを開き、マイマップにKMLデータをアップロードすると、Google map上にKMLデータのアイコンが表示されるようになる。また、この段階で数多くある防火水槽とスタンドパイプそれぞれに番号を振り分け、判別できるようにした。

<img width="1280" alt="2019-01-08 18 39 24" src="https://user-images.githubusercontent.com/33411765/50824284-87185480-1379-11e9-908a-eed2cadc1d9f.png">
　これはPCのウェブプラウザ上でのGoogle mapでKMLデータを表示した図だ。

　Google mapはiPhoneで開くことができるため、PC上のマイマップデータを共有してiPhoneでも開くことができる。また、KMLデータを使用しているため、PCのマイマップ上にあるレイヤ機能やライン描画は使用できない。そのため、防火水槽とスタンドパイプの位置情報に経由地登録を行い、それぞれいくつかのルートに分けて手作業でルートを作成した。

![img_5448](https://user-images.githubusercontent.com/33411765/50824627-6f8d9b80-137a-11e9-9643-3ad61973aea1.PNG)
　これはiPhoneでGoogle mapを開き、同じくKMLデータを表示した図だ。


### 1-3. 撮影方法

　続いてTHETAを使用した撮影方法だが、最も重要なのはバッテリーだ。THETAとiPhoneのどちらもバッテリーが切れたらそこまでなので、いかにバッテリーを上手く扱うかが肝になる。iPhoneは充電しながらの走行も可能だが、THETAはそれができない。更にマックスまで充電するのにはおよそ200時間かかる。十分な時間を持って効率的に行うことが重要であることを忘れてはならないのだ。

　本題に入ると、まずはTHETAとiPhoneをWi-fiで接続し、THETA専用のアプリで撮影を開始する。その際今回は８秒毎に自動で撮影されるモードに切り替えておく。Mapilleryと違いm毎など距離での設定ができないので、できるだけ同じペースで走行することが必要だ。信号待ちや機会の設定中なども自動的にシャッターが押されてしまうことを忘れてはならない。加えて、大和市は平坦な道が少なく、坂を登って降りての繰り返しであるところが少なくない。その際は上り坂と下り坂で明らかにシャッター数が変わってしまう。これはTHETA撮影のデメリットだ。

　もう１つの課題としてTHETAとiPhoneの接続が途中で切れてしまうという事件が多々起きる。走行中、iPhoneではルートを表示しているため接続が切れていることに気づかない。古いiPhoneなど他の端末を持っているのならば、２つ以上使用して常に接続状態を確認できるようにすることを勧める。


### 1-4. 大和市の防災状況

　大和市では今、専用の"ヤマトSOS"というアプリを使って防災活動を呼びかけている。内容は消火栓やAED、防火水槽とスタンドパイプの位置情報を提示するだけでなく、災害時の早急な情報やイベントのお知らせ、更にはブザーやライトの機能までついている。これ等を１つにまとめて提供できるのだから、アプリが一番効率がいいと藤田さんはおっしゃっていた。勿論大和市以外でも市区町村ベースでの災害防災アプリなどは存在するが、ここまでコンテンツも多く、使いやすさが重視されているのは数少ないのではないかと思う。ここから、大和市がいかに防災に力を入れているかが見受けられる。

　今回実際に撮影を行うにあたって消防本部から自転車をお借りすることになった。そのため何度も消防本部に足を踏み入れたが、私が想像していたよりも遥かに多くのペースで出動しており、自転車で市内を回っている際も何度も大和消防車や救急車を見かけた。そのくらい実際には多くの事故が発生しており、それを大和消防の方々が救っているのだと気付いた。

![500px-yamato_city_fire_station](https://user-images.githubusercontent.com/33411765/50824346-b4650280-1379-11e9-9a2e-e99e763fc4a3.jpg)
　こちらが大和市消防本部。


　立ち寄った際に一度藤田さんが本部の中を簡単に案内してくださった。事務局や出動場所だけでなく、食堂や休憩室、寝床までを実際に見せてくださった。その内どの瞬間を取っても何かあった時に一刻も早く出動できるようにと、市の安全を第一に考える姿勢が伺えた。最も興味深かったのは、乾燥室が多くあり、その中は広くてブーツがすぐに乾くようにと引っ掛ける専用の鉄棒がいくつもあったことだ。藤田さんによると、消防士は乾燥が命だ、水分があってはならないから乾燥は入念に行うのだと言う。

　また、大和市は想像以上に広く、8駅分に及ぶ。中には高速道路や公園、険しい山道が続くところもあった。都内に比べると勿論人は少ないが、だからこそ地元の繋がりを大切にし、ご近所さん同士で集まったり家族同士で遊ぶ微笑ましい瞬間を何度も目にした。私が苦しながらに自転車を漕いでいると、「何してるの？大変だね、頑張ってね」と声をかけてくださる心優しい方もたくさんいらっしゃり、心暖かく人を大切にする市だと感じた。

### 1-5.データのアップロード方法

　RICOH THETA Sで撮影したデータをPCのウェブブラウザ上でMapillaryにアップロードする方法を述べていく。撮影データは商用利用可能なオープンデータライセンス(CC BY-SA 4.0)として公開・共有可能な Mapillary (https://www.mapillary.com) を用いた。まずは撮影時と同様iPhoneとTHETAをWi-fiで接続し、THETA専用アプリを開く。アプリ内のカメラ内映像のところにある撮影したデータを選択し、iPhoneのカメラロールへ転送する。この作業が本当に時間がかかるのだ。ストリートビュー撮影の場合、一度に大量のデータを転送することになるため転送中に接続が切れてしまい始めからになってしまったり、iPhone,THETAの両方の充電と容量をよく消費ため、途中でどちらかの充電が切れてしまってはそこまでだ。（私のiPhoneの場合、200個のデータを一度転送するのに充電の半分以上を消費してしまう。）また、転送するデータを選択する際、iPhoneのカメラロールやPCのように一度に多くのデータを選択することが出来ない。大量のデータを１つ１つ選択しなければならないのも時間がかかる要因だ。

　カメラロールへの転送は、およそ１分間で６つのデータが完了する程のペースだ。寝る前に多くのデータを一度に選択していても、起きた時には基本的に接続かTHETAの充電が切れて始めからの状態になっている。THETAはiPhoneと違い充電しながら使うことが出来ないからである。何か別の作業をしながらおよそ200~300程度のデータを分けて転送していくのがリスクも少なくある程度効率も良く進める方法だ。

　時間をかけてカメラロールへの転送が完了したら、（iPhoneのカメラロールは360度対応していないので180度表示になってしまう）それ等のデータをPCへ移していく。iPhoneとMacであれば、Airdropが最も早く効率の良い手段である。ここのデータ移動は時間がかからず、ストレスもなくスムーズに行うことができる。

　PCに移したデータをウェブプラウザ上でMapillaryを開き、アップロードしていく。Mapillary画面上の左にあるアップロードボタンを押し、データを選択すれば簡単にアップロードできるが、どれにせよ良いネットワーク環境で行うことを勧める。今回は約2,100枚もの360°パノラマ画像をアップロードし公開した。
　
<img width="1280" alt="2019-01-08 19 15 29" src="https://user-images.githubusercontent.com/33411765/50824406-df4f5680-1379-11e9-92cc-2db39ef4bd49.png">
　これはPCのウェブプラウザ上でのMapillaryアップロード画面。


## 2. 研究結果

　計4日間の撮影を行い、撮影された360°パノラマ画像データは、スマートフォン経由でPC上にデータを移送し、ウェブブラウザ版Mapillaryを用いることで約2,100枚もの360°パノラマ画像をアップロードし公開した。撮影実施エリアは大和市内相模鉄道本線より北側エリアを移動距離で約28.0 km、自転車に360° カメラを固定する形で、防火水槽、スタンドパイプ設置エリアの撮影は網羅することが出来たが、その南側に関しては撮影することが出来ていない。駅で言うと大和市内8駅の内、中央林間駅、南林間駅、相模大塚駅、鶴間駅、つきみ野駅周辺は網羅出来た。

![img_5439](https://user-images.githubusercontent.com/33411765/50824426-eaa28200-1379-11e9-987d-704b3e1c40ba.PNG)
　
 星マークがついているポイントは私が撮影できた防災設備だ。

　撮影データは、ミーティングをする以前AEDを回っていた時や、それぞれ行き帰りのデータも含まれるため、より多くの道を撮影することが出来た。


## 3. 考察

　撮影された360°パノラマ画像より読み取れる防災設備設置エリア周辺のランドスケープの判読を基に、個別の防火水槽及びスタンドパイプを識別するための一意の名称定義ルールの検討も行った。まず、命名ルールの要素にはどのようなものがあるのか。字、ランドマーク、方角、現在の地名、傾斜の上下などだ。イメージしやすいものとしてバス停の名前やコンビニの店舗名などがある。例えば、現在の地名＋位置する方角などの組み合わせがほとんどだ。

　また、過去に大和市では新たな財源を確保し、市民サービスの向上及び地域の活性化を図るために市内4地域を運行するコミュニティバス「やまとんGO」のバス停の名称を決定するネーミングライツを実施した。これは市民の移動手段を確保維持していくために地域で公共交通を支えながら、企業や店舗のイメージアップとPRに役立つツールとして活用するというものだ。これには条件があり、ただ好き勝手にバス停の名前を付けられるわけではなく、バス停に近接している事業所や店舗等の名前を使用するという条件だ。

<img width="1280" alt="2019-01-09 15 24 27" src="https://user-images.githubusercontent.com/33411765/50881313-94d6e400-1424-11e9-9700-90e4ed648679.png">
　
 これがその募集に関する詳細である。

　今回はバス停のように近辺に必ず事業所や店舗があるとは限らないし、この募集のように企業や店舗のPRのために行うわけでもない。防災設備は市内に無数にあるし、情報収集から防火水槽スタンドパイプに関しては、住宅地の中や公園の中など、近接にランドマークが存在しない場合も多い。どの防災設備にも当てはまる命名ルールを検討するのであれば、ランドマークを必ず取り入れることは不可能だ。加えて、数が多いが故に多数の防災設備が近隣に密接している場合も多い。そういった場合の判別も行わないとならないのだ。

　これらの情報を踏まえて私が検討した命名ルールはこれだ。
 **”周辺のランドマーク名+前” or ”現在の地名” （複数ある場合）+ ”傾斜の上下” or ”方角”（複数ある場合）-”その中での方角” + “防災設備名”**


<img width="1280" alt="2019-01-10 0 41 47" src="https://user-images.githubusercontent.com/33411765/50910710-b7431e80-1471-11e9-9aa7-f84a0f0437e9.png">


ex) 大和市コミュニティセンター上草柳会館前スタンドパイプ、深見西防火水槽、鶴間南三丁目-南防火水槽

　ここでいうランドマークとは、事業者や店舗等だけでなく公園や駅などの公共施設も含まれる。数が多いため、少しでも頭に入りやすいよう、多くても３つの要素から成り立たせ、できるだけわかりやすくシンプルにした。

## まとめ

　神奈川県大和市内における全防火水槽とスタンドパイプに固有名詞を定義することを目的として、その設置状況基礎データとなるストリートビュー撮影を行った。撮影されたデータは、スマートフォン経由でPC上にデータを移送し、ウェブブラウザ版Mapillaryを用いることで約2,100枚もの360°パノラマ画像をアップロードし公開した。撮影実施エリアは大和市内相模鉄道本線より北側エリアを移動距離で約28.0 km、自転車に360° カメラを固定する形で、防火水槽、スタンドパイプ設置エリアの撮影は網羅することが出来たが、その南側に関しては撮影することが出来ていない。

　撮影された360°パノラマ画像より読み取れる防災設備設置エリア周辺のランドスケープの判読を基に、個別の防火水槽及びスタンドパイプを識別するための一意の名称定義ルールの検討も行った。大和市内に無数にあるこれらの防災設備周辺には、想定よりも近接にランドマークが存在しない場合も多く、特徴的で地元住民に違和感なく受け入れられる命名ルールを検討した結果、”周辺のランドマーク名+前” or ”現在の地名” （複数ある場合）+ ”傾斜の上下” or ”方角”（複数ある場合）-”その中での方角” + “防災設備名”という命名規則を提唱した。

　準備計画の段階では、撮影日４日間で大和市内全ての防火水槽とスタンドパイプを網羅する道の撮影を終える予定であった。しかし研究結果で述べたように、効率の悪さと準備不足によって達成することができなかったのだ。私の結果から述べると、天気や体調のコンディションが整った上で後３日間あれば大和市内をコンプリートできると思う。勿論それは、9:00~16:00までみっちり撮影を行う場合だ。間にそれぞれの充電補充も兼ねて休憩は必須であるし、前述の通り現場では何が起こるかわからないので、1日以上の予備日を予め設定しておくことも必要だ。加えて、効率よく撮影を行うために現場に向かう前にシュミレーションを行なっておくことを勧める。

　私は、THETAとiPhoneのバッテリーと容量に悩まされ、そこに多くの時間を取られてしまった。可能であればTHETA、iPhone共に2台ずつ用意し、iPhoneはstrava記録とTHETAの撮影画面で接続を常に確認できるように1台、ルート確認のためにもう1台を使うと効率が良い。THETAは充電か容量がなくなってしまった際にもう1台を使用し、その間にバッテリーを補充するといった工夫ができる。もしくは、RICOH THETA Sよりも値段の高いTHETAを使用すると、バッテリーの持ちも良く、容量も多く、更には充電しながらの撮影も可能になる。また、THETAとiPhoneだけでなくPCの容量も十分に空けておくとなおスムーズであるし、作業を行うネットワーク環境も重要だ。

　もしこの研究に挑戦したい人がいるのであれば、私の経験から得た数多くの反省を活かして防災設備の固有名詞化まで完了して欲しいと願う。

## 参考文献

【KMLファイルをgooglemapに移す】http://www.ic.daito.ac.jp/~mizutani/gis/kml_at_googlemap.html
【マイマップ作成方法】https://appllio.com/how-to-use-google-map-mymap-streetview
【大和市ホームページ】http://www.city.yamato.lg.jp/index.html
【Mapillaryアップロード方法】https://qiita.com/kochizufan/items/90b7f8902409231e8fe9
【字”あざ”とは】https://kotobank.jp/word/字-24958


