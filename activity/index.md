[Top](../)

---

# 活動内容について
## Qiita
UdonGraphの入門記事などを掲載しています！  
現在は[UdonGraphの基礎に関連するもの](https://qiita.com/Sayamame/items/c36a1a87d4189d51099c)、[Udon自体についてのもの](https://qiita.com/Sayamame/items/69ba9e25390f8068d5a6)、[プレイヤー関連のUdonGraphノードの抜粋・説明](https://qiita.com/Sayamame/items/10ea6dc48ebb6d3e8655)の記事があります。  
最近は更新出来ていません…

## Zenn
[Udon関連の私的メモ](https://zenn.dev/sayamame/scraps/90f95397828250)を掲載しています。あまり活動していません。  

## Misskey
KineL式ビデオプレイヤーの製作者である[りら](https://misskey.niri.la/@ni_rilana)さんが運営している、主にVRChatter向けなサーバー「[にりらみすきー部](https://misskey.niri.la/)」にて、副管理人とモデレーターを担当しています。  
もちろん、VRChat以外の話題も歓迎されています！

## GitHub
<details><summary>GitHub上での活動/リポジトリ</summary>

### [KiseteNe for MA](https://github.com/Sayamame-beans/KiseteNe-for-MA)
着せ替え支援ツール「キセテネ」をprefab状態の衣装にも利用可能なように改変したものです。  
Modular Avatar等との併用が前提。[Booth](https://sayamame-beans.booth.pm/items/5057270)と[VPM](https://sayabeans.github.io/vpm/)で配布中。

---
### [Avatar Optimizer](https://github.com/anatawa12/AvatarOptimizer)
VRChat向けの非破壊式アバター最適化ツールです。  
anatawa12さんのリポジトリで、私はCollaboratorです。  
主にドキュメントの調整、Localizationの調整、PRのレビューを行っています。

---
### [VRCPhysBone-Relocator](https://github.com/Sayamame-beans/VRCPhysBone-Relocator)
PhysBoneの"Root Transform"設定を確認して、そのGameObjectの位置にPBコンポーネントを移動させるUnityエディタ拡張です。  
他の移動操作も可能にする更新を予定していますが、まだ手を付けられていません。  
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

---
### [Discord to Misskey](https://github.com/Sayamame-beans/Discord-to-Misskey)
Discordに流れてきたメッセージをMisskeyに転送するためのPython製のDiscord Bot等です。  
WIPで、Misskeyへの送信処理は出来ていて、Discord Bot部分が未完成だったはず?

---
### VRCInfo-DB(仮名)
VRChat関連のバグ情報や対処法等を集めるDB/Webサイト。  
準備中なのでリポジトリは非公開。  
anatawa12さんと共同開発予定?

---
### その他
- [Modular Avatar](https://github.com/bdunderscore/modular-avatar)  
issue情報を整理して[提供](https://misskey.niri.la/notes/9nh58d2xgt)。  
ドキュメント調整のPRを用意中です。(もう少し時間が掛かりそう)

- [MisskeyEmojiBot](https://github.com/niwaniwa/MisskeyEmojiBot)  
Misskeyの絵文字登録と承認を簡略化するためのGo製のDiscord Botです。  
りらさんのリポジトリですが、本人が最近リソース不足になっているので、そのうち自分で書いたissueを消化しようと思っています。

- [misskey.niri.la](https://github.com/niri-la/misskey.niri.la)  
にりらみすきー部のソースコードのリポジトリ。  
[本家Misskey](https://github.com/misskey-dev/misskey)と異なる部分が少しあります。  
主にanatawa12さんがPRを担当していて、私はレビューとissue整理等をやっています。

---
</details>

## Booth
<details><summary>販売商品の説明</summary>

### [キセテネ for MA【無料】](https://sayamame-beans.booth.pm/items/5057270)
Prefabの衣装も調整出来るよう[キセテネ](https://shivi.booth.pm/items/2332420)を改変したものです。  
(キセテネはMIT Licenseの下で改変/再配布が認められています)  
※Modular Avatar等と併用する前提で、着せる機能はありません

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

## 非公開の開発物
### Server Controller
Minecraftサーバーの起動管理、ホワイトリスト登録等を行うためのPython製のDiscord Botです。  
コマンドを叩くとwolやTCP通信を使用して別PCのMinecraftサーバーを(電源ごと)起動したりします。  
雑に作っちゃったのでソースが公開出来る状態じゃありません。  
公開していないのを良いことに、wolで他のPCも起動出来るようにしています。(管理者限定)
