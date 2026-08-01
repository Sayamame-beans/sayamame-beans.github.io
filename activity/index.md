# 活動内容について
## VRChat
[Booth](https://sayamame-beans.booth.pm/)や[GitHub](https://github.com/Sayamame-beans)、[VPMリポジトリ](https://sayabeans.github.io/vpm/)でUdonギミックやエディタ拡張等を配布しています。(基本的に無料)  
また、ALCOM/AAOの開発のお手伝いをしたり、VRChatの更新情報等の非公式翻訳を行ったり、VRChat本体やSDK等に関するCanny(バグ報告/機能要望)の作成、VRCユーザーのサポート対応等をしています。  
(VRChat本体を[コミュニティ主導で翻訳](https://docs.vrchat.com/docs/suggesting-localization-changes)するためのサーバーで活動を行っていた時期もありましたが、最近は忙しくて殆ど眺めるだけになっています。)

MainMenu 2.0 OpenBetaの時期には、(Cannyの検索性が悪いため)[gistにCannyを全て列挙](https://gist.github.com/Sayamame-beans/df362b6f9e526920a046f78aca2463d6)し、重複を纏め、日本語で概要を記載したりしていました。  
現在は[VRChatのCannyを横断的に検索出来るWebサイト](https://vrchat-canny.hackebein.dev/)があるので、こんなことをする必要はないですね！

VRChat関連の非公式翻訳を発信する際に、X/TwitterやMisskeyで使用している主なハッシュタグは以下の通りです。
- #VRChat更新速報  
VRChat(Live)のリリースアナウンスの非公式翻訳が主な対象となるタグです。
- #VRChatベータ情報  
VRChat(OpenBeta)のリリースアナウンスの非公式翻訳が主な対象となるタグです。
- #VRChat関連翻訳  
Developer UpdateやVRChatのブログ投稿等の非公式翻訳が主な対象となるタグです。
- #VRChat_Canny情報  
作成したCannyや重要度が高そうなCanny等を共有する際に使用しているタグです。
- #VRChatCreatorCompanion更新  
VCCの更新情報の非公式翻訳が主な対象となるタグです。

参加しているサポートコミュニティは以下の通りです。
- VRCβフォース
- VRCUnity勉強会
- Modular Avatar & NDMF
- もち家の実家サーバー
- 開発補助(プライベートサーバー)

## Misskey
KineL式ビデオプレイヤーの製作者である[りら](https://misskey.niri.la/@ni_rilana)さんが運営している、主にVRChatter向けなサーバー「[にりらみすきー部](https://misskey.niri.la/)」にて、副管理人とモデレーターを担当しています。  
もちろん、VRChat以外の話題も歓迎されています！

また、misskey-devとして本家Misskeyの開発にも参加しています。

## Qiita
UdonGraphの入門記事などを掲載しています！  
現在は[UdonGraphの基礎に関連するもの](https://qiita.com/Sayamame/items/c36a1a87d4189d51099c)、[Udon自体についてのもの](https://qiita.com/Sayamame/items/69ba9e25390f8068d5a6)、[プレイヤー関連のUdonGraphノードの抜粋・説明](https://qiita.com/Sayamame/items/10ea6dc48ebb6d3e8655)の記事があります。  
最近は新しい内容を投稿出来ていません…

## Zenn
[Udon関連の私的メモ](https://zenn.dev/sayamame/scraps/90f95397828250)を掲載しています。あまり活動していません。  

## GitHub
<details><summary>GitHub上での活動/リポジトリ</summary>

### [KiseteNe for MA](https://github.com/Sayamame-beans/KiseteNe-for-MA)
着せ替え支援ツール「キセテネ」をprefab状態の衣装にも利用可能なように改変したものです。  
独自機能としてUndo/Redoへの対応と調整値の保存/読み込み機能があります。  
"着せる"機能を無くし、着せ替え時の衣装の調整に特化させているため、Modular Avatar等との併用が前提です。  
[Booth](https://sayamame-beans.booth.pm/items/5057270)と[VPM](https://sayabeans.github.io/vpm/)で配布中。

---
### [ALCOM/vrc-get](https://github.com/vrc-get/vrc-get)
[ALCOM(アルコム)](https://vrc-get.anatawa12.com/ja/alcom/)はVRChat Creator Companion(VCC)のオープンソースな非公式代替ツールです。  
主にSNSでのサポート対応や日本語対応、原文(英語)の調整、一部機能の実装を行っています。

---
### [Avatar Optimizer](https://github.com/anatawa12/AvatarOptimizer)
VRChat向けの非破壊式アバター最適化ツールです。  
anatawa12さんのリポジトリで、私はCollaboratorです。  
主にドキュメントの調整や日本語対応、PRのレビューを行っています。

---
### [Misskey](https://github.com/misskey-dev/misskey)
misskey-devとして本家Misskeyの開発に参加し、issue整理や一部の機能改善のPRなどを行っています。

---
### [misskey.niri.la](https://github.com/niri-la/misskey.niri.la)  
Misskeyサーバー「にりらみすきー部」のソースコードのリポジトリ。  
本家Misskeyとは少し異なる部分があります。  
主にanatawa12さんがPRを担当していて、私はレビューやissue整理、一部の機能改善のPRなどを行っています。

---
### [Upload without pre-check](https://github.com/Sayamame-beans/Upload-without-preCheck)
VRCSDKのビルド前チェックをスキップしてアバターをアップロードするためのメニュー項目を追加するツールです。  
AAO等の非破壊改変ツールによってのHard Limitを下回るにも関わらず、ビルド前チェックでHard Limitに引っ掛かってしまいアップロードが行えない問題を解決します。  
(※VRCSDKにはビルド後チェック(アップロード直前のチェック)の仕組みもあるため、制限を超過している場合にはアップロードに失敗します)  
[VPM](https://sayabeans.github.io/vpm/)で配布中。

VRCSDKの更新により、現在はHard Limitを超過していてもビルドを開始出来るようになっているため、本ツールは使う必要がなくなりました。

---
### [VRCPhysBone-Relocator](https://github.com/Sayamame-beans/VRCPhysBone-Relocator)
PhysBoneの"Root Transform"設定を確認して、そのGameObjectの位置にPBコンポーネントを移動させるUnityエディタ拡張です。  
他の移動操作も可能にする更新を検討していますが、全く手を付けられていません…  
[Booth](https://sayamame-beans.booth.pm/items/3872837)にも公開しています。

---
### [VRC_AFK_AutoMuter](https://github.com/Sayamame-beans/VRC_AFK_AutoMuter)
OSCを使用して、VRChatでAFKしている時に自動的にミュートするPython製のソフトです。  
OSCQueryには非対応です。(実行時にポートを変更することは出来ます)  
[Booth](https://sayamame-beans.booth.pm/items/3696828)にも公開しています。

---
### [QuoteBot](https://github.com/kobi32768/quotebot)
Discordのメッセージリンクが貼られた際に、その内容を送信するKotlin製のDiscord Botです。  
kobi32768さんのリポジトリで、私はCollaboratorです。

---
### [VRCLogDataCollector](https://github.com/Sayamame-beans/VRCLogDataCollector)
とあるCannyの調査のために作った、VRChatのログファイルからインスタンスjoinに掛かっている時間を抽出するPython製のソフトです。  
非常に雑な作りで、並列処理もしていないので動作は遅いのですが、目的は達成出来ています。  
あれからしばらく経ち、VRChatのログ出力内容に変更があったはずなので、正常に動作しなくなっている可能性があります。

---
### [Discord to Misskey](https://github.com/Sayamame-beans/Discord-to-Misskey)
Discordに流れてきたメッセージをMisskeyに転送するためのPython製のDiscord Bot/Misskey Botです。  
WIPで、Misskeyへの送信処理は出来ていて、Discord Bot部分が未完成だったはず…まだ手を付けられていません。

---
### [mi-reminder](https://github.com/niri-la/mi-reminder)
ユーザーがメンションして呼び出すことで利用出来る、リマインド用のRust製Misskey Botです。  
WIPで、DB周りなどの準備が出来ていなかったはず…まだ手を付けられていません。

---
### その他
- [Modular Avatar](https://github.com/bdunderscore/modular-avatar)  
bd_さんのリポジトリです。  
issueを整理したり、細かな機能改善のPRを行ったりしています。

- [MisskeyEmojiBot](https://github.com/niwaniwa/MisskeyEmojiBot)  
Misskeyの絵文字登録と承認を簡略化するためのGo製のDiscord Botです。  
りらさんのリポジトリですが、本人が最近リソース不足になっているので、そのうち自分で書いたissueを消化しようと思っています。

---
</details>

## Booth
<details><summary>販売商品の説明</summary>

### [キセテネ for MA【無料】](https://sayamame-beans.booth.pm/items/5057270)
Prefabの衣装も調整出来るよう[キセテネ](https://shivi.booth.pm/items/2332420)を改変したものです。  
(キセテネはMIT Licenseの下で改変/再配布が認められています)  
※Modular Avatar等と併用する前提で、着せる機能はありません。  
独自機能としてUndo/Redoへの対応と調整値の保存/読み込み機能があります。  

VPMに対応しており、VCCに追加可能です。  
付属のunitypackageは[VPAI](https://github.com/anatawa12/VPMPackageAutoInstaller)を利用して作成したものです。

ソースコードを[公開](https://github.com/Sayamame-beans/KiseteNe-for-MA)しています。

---
### [【無料】アニメーション同期システム【UdonGraph】](https://sayamame-beans.booth.pm/items/3645740)
UdonGraph製のアニメーションを自動で同期するギミックです。  
付属のprefabをHierarchyに置いて、同期したいAnimatorをセットするだけで利用出来ます。  
フレンドが、SDK2の時は公式のComponentで簡単に同期出来たのに、SDK3だと出来ない……と言っていたので作りました。  

以下の機能を備えています。
- 自動同期の周期を変更可能
- 同期完了時に他のUdon向けにイベントを発火可能
- 他のUdonから手動同期の指示が可能

また、prefabは2つあり、
- Light版  
各Animatorの全レイヤーについて、Animation1つに対して時間を同期可能
- Full版  
各Animatorの全レイヤーについて、パラメーター、再生中のステート、時間が同期可能(各ステートにMultiplier Parameterを設定することで、速度も同期可能)  

こちら、[黄金楽園](https://vrchat.com/home/world/wrld_2ebe7a5f-a0b0-4459-9452-1583480d9b43)や[ぽこピーランド](https://vrchat.com/home/world/wrld_6f55a286-b851-4d3e-8933-e7a31138edd7)(?!)などでご利用いただいているようです。(ありがとうございます！)

---
### [【無料】動画プレイヤー連携 BGM自動停止ギミック【UdonSharp】](https://sayamame-beans.booth.pm/items/5037614)
動画プレイヤーの再生状態に応じて、ワールドBGMのオンオフを自動で切り替えるためのUdonSharp製ギミックです。  
現在はGameObjectのアクティブ/非アクティブを切り替えることによって実現されています。  
(要望があればAudioSourceに対する切り替え等にも対応いたします。)

現在対応している動画プレイヤーは以下の通りです。
- [iwaSync3](https://hoshinolabs.booth.pm/items/2666275)
- [KineL式ビデオプレイヤー](https://kinel.booth.pm/items/2758684)

あっと様のご要望に応じて作成しました。  
[澄夏町学校 プール開放日 -School Swimming Pool in Summer-](https://vrchat.com/home/world/wrld_1051d8dc-7caf-4a1b-ba98-5e6a60f489ca)にてご利用いただいています。(ありがとうございます！)

---
### [【無料】アナログ時計【Udon配布】](https://sayamame-beans.booth.pm/items/3321518)
UdonGraph製のアナログ時計です。  
秒針が動くと分針が少しずつ動くところがこだわりポイント。  
また、秒針の音を鳴らすことが出来ます。  
Udonを配布するのが主目的だったので、付属のprefabはサンプル用だったのですが、マテリアル等を付けたらそれっぽくなったのでそのままご利用いただけます。  
おまけ版を買うと卓上時計も付いてきます。  

[Q's Library](https://vrchat.com/home/world/wrld_16008b3b-0802-475d-b58c-39faeb624fef)など幾つかのワールドでご利用いただいています。(ありがとうございます！)

---
### [【無料】スイッチ数種類【説明付きUdon配布】](https://sayamame-beans.booth.pm/items/3343488)
UdonGraph製のスイッチです。  
Interactしてオンオフを切り替えるタイプと、オブジェクトを入れ替えるタイプがあります。(それぞれ、ローカル版とグローバル版あり)  
ただ、3Dモデルは付属していません(ただの小さなCube)  

UdonGraphの中身を覗くと説明がついているので、Udonの勉強にも使えるかも…？

---
### [【無料】アニメーション操作盤【UdonGraph】](https://sayamame-beans.booth.pm/items/4727851)
「[アニメーション同期システム](#無料アニメーション同期システムudongraph)」と連携して、アニメーションを操作することが出来るUdonGraph製のギミックです。  
付属のprefabを置き、Inspectorでアニメーション同期システムのGameObjectをセットすることで使用出来ます。

以下の機能を備えています。
- 操作対象のAnimatorの切り替え(アニメーション同期システムに登録されているのみ)
- 操作対象のレイヤーの切り替え
- 操作対象のAnimator名、レイヤー名の表示
- アニメーション同期システムに手動同期を指示
- 時間の操作(再生中のstateの再生時間を操作可能)
  - スライダー操作
- 速度の操作
  - スライダー操作
  - ボタン操作(-2.0, -1.5, -1.0, -0.5, 0.0, 0.5, 1.0, 1.5, 2.0)

---
### [【無料】テレポーター【説明付きUdon配布】](https://sayamame-beans.booth.pm/items/3519012)
UdonGraph製のテレポーターです。  
Interactするとテレポート出来ます。  
こちらも3Dモデルは無く、Cubeです。(3Dモデルが作れない)  

UdonGraphの中身を覗くと説明がついているので、Udonの勉強にも使えるかも…？

---
### [【無料】デジタル時計【Udon配布】](https://sayamame-beans.booth.pm/items/4681986)
UdonGraph製のデジタル時計です。  
とってもシンプルな見た目のサンプルしか付いていませんし、UdonGraphの説明も付属していないのですが、あまり複雑ではないのでUdonの勉強にも使えそうです。

---
### [【VRChat】AFK時に自動でミュートするOSCツール](https://sayamame-beans.booth.pm/items/3696828)
Windows上で動作するOSCツールです。  
AFKに移行した時に、パラメーターの変化を検知して、VRCのマイクをミュートします。  
利用には、OSCが有効になっていることと、AFK検知が有効になっていること、ミュートが切り替え式の設定であることが必要です。  

ソースコードを[公開](https://github.com/Sayamame-beans/VRC_AFK_AutoMuter)しています。(Windows以外でもご利用いただけるかも?)

---
### [VRCPhysBone-Relocator【無料 / Free】](https://sayamame-beans.booth.pm/items/3872837)
PBコンポーネント類の配置を移動させるためのUnityのエディタ拡張です。  
PhysBoneの"Root Transform"設定を確認して、そのGameObjectの位置にPBコンポーネントを移動させることが出来ます。  
VRM Converter for VRChatでVRoidから変換したアバターなどでよく見られる、「1つのGameObjectに大量のPBコンポーネントが含まれていて、どのコンポーネントがどのボーンと対応するか分からない」ような場合などで役立ちます！

ソースコードを[公開](https://github.com/Sayamame-beans/VRCPhysBone-Relocator)しています。  
最近更新が滞っていますが、近いうちに更新して自分のVPMリポジトリに追加したいと思っています。

---

</details>

## その他
### Server Controller
Minecraftサーバーの起動管理、ホワイトリスト登録等を行うためのPython製のDiscord Botです。  
コマンドを叩くとWoLやTCP通信を使用して別PCのMinecraftサーバーを(電源ごと)起動したりします。  
雑に作っちゃったのでソースが公開出来る状態じゃありません。  
公開していないのを良いことに、WoLで他のPCも起動出来るおまけ機能を付けています。(管理者限定)
