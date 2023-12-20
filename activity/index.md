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

---
### [KiseteNe for MA](https://github.com/Sayamame-beans/KiseteNe-for-MA)
---
着せ替え支援ツール「キセテネ」をprefab状態の衣装にも利用可能なように改変したものです。  
Modular Avatar等との併用が前提。[Booth](#キセテネ-for-ma無料)と[VPM](https://sayabeans.github.io/vpm/)で配布中。

---
### [Avatar Optimizer](https://github.com/anatawa12/AvatarOptimizer)
---
VRChat向けの非破壊式アバター最適化ツールです。  
anatawa12さんのリポジトリで、私はCollaboratorです。  
主にドキュメントの調整、Localizationの調整、PRのレビューを行っています。

---
### [VRCPhysBone-Relocator](https://github.com/Sayamame-beans/VRCPhysBone-Relocator)
---
PhysBoneの"Root Transform"設定を確認して、そのGameObjectの位置にPBコンポーネントを移動させるUnityエディタ拡張です。  
他の移動操作も可能にする更新を予定していますが、まだ手を付けられていません。  
[Booth](#vrcphysbone-relocator無料--free)にも公開しています。

---
### [VRC_AFK_AutoMuter](https://github.com/Sayamame-beans/VRC_AFK_AutoMuter)
---
OSCを使用して、VRChatでAFKしている時に自動的にミュートするPython製のソフトです。  
OSCQueryには非対応です。(実行時にポートを変更することは出来ます)  
[Booth](#vrchatafk時に自動でミュートするoscツール)にも公開しています。

---
### [QuoteBot](https://github.com/kobi32768/quotebot)
---
Discordのメッセージリンクが貼られた際に、その内容を送信するKotlin製のDiscord Botです。  
kobi32768さんのリポジトリで、私はCollaboratorです。

---
### [VRCLogDataCollector](https://github.com/Sayamame-beans/VRCLogDataCollector)
---
とあるCannyの調査のために作った、VRChatのログファイルからインスタンスjoinに掛かっている時間を抽出するPython製のソフトです。  
非常に雑な作りで、並列処理もしていないので動作は遅いのですが、目的は達成出来ています。

---
### [Discord to Misskey](https://github.com/Sayamame-beans/Discord-to-Misskey)
---
Discordに流れてきたメッセージをMisskeyに転送するためのPython製のDiscord Bot等です。  
WIPで、Misskeyへの送信処理は出来ていて、Discord Bot部分が未完成だったはず?

---
### VRCInfo-DB(仮名)
---
VRChat関連のバグ情報や対処法等を集めるDB/Webサイト。  
準備中なのでリポジトリは非公開。  
anatawa12さんと共同開発予定?

---
### その他
---
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
現時点(2023/05/09)で販売している商品について、[以前Misskeyで投稿した簡易説明](https://misskey.niri.la/notes/9e2jdr64qs)を引用します。
<details><summary>内容</summary>

私が[Booth](https://sayamame-beans.booth.pm/)で出している商品達をご紹介！(今のところ全て無料！)  

---
### 【無料】アニメーション同期システム【UdonGraph】
---
UdonGraph製、アニメーションを自動で同期するギミック！  
付属のprefabをHierarchyに置いて、同期したいAnimatorをセットするだけでOK！  
フレンドが、SDK2の時は公式のComponentで簡単に同期出来たのに、SDK3だと出来ない……と言っていたので、作っちゃいました！  

以下の機能を備えています。
- 自動同期の周期を変更可能
- 同期完了時に他のUdon向けにイベントを発火可能
- 他のUdonから手動同期の指示が可能

また、prefabは2つあり、
- Light版  
各Animatorの全レイヤーについて、Animation1つに対して時間を同期可能
- Full版  
各Animatorの全レイヤーについて、パラメーター、再生中のステート、時間が同期可能(各ステートにMultiplier Parameterを設定することで、速度も同期可能)  

こちら、[黄金楽園](https://vrchat.com/home/world/wrld_2ebe7a5f-a0b0-4459-9452-1583480d9b43)や[ぽこピーランド](https://vrchat.com/home/world/wrld_6f55a286-b851-4d3e-8933-e7a31138edd7)(?!)などでご利用いただいているようです！(ありがとうございます！)  

---
### 【無料】アナログ時計【Udon配布】
---
UdonGraph製の時計！  
秒針が動くと分針が少しずつ動くところがこだわりポイント。  
また、秒針の音が鳴ります。  
一応Udonを配布するのが主目的だったので、付属のprefabはサンプル用…だったのですが、マテリアルとか付けたらそれっぽくなったのでそのままご利用いただけます。  
おまけ版を買うと卓上時計も付いてきます。  

[Q's Library](https://vrchat.com/home/world/wrld_16008b3b-0802-475d-b58c-39faeb624fef)など幾つかのワールドでご利用いただいています～(ありがとうございます！)  

---
### 【無料】スイッチ数種類【説明付きUdon配布】
---
UdonGraph製のスイッチ！  
Interactしてオンオフを切り替えるタイプと、オブジェクトを入れ替えるタイプがあります。(それぞれ、ローカル版とグローバル版あり)  
ただ、3Dモデルは付属していません(ただの小さなCube)  

UdonGraphの中身を覗くと説明がついているので、Udonの勉強にも使えるかも…？  

---
### 【無料】テレポーター【説明付きUdon配布】
---
UdonGraph製のテレポーター！  
Interactするとテレポート出来ます。  
こちらも3Dモデルは無くて、Cubeです…(3Dモデル作れない)  

UdonGraphの中身を覗くと説明がついているので、Udonの勉強にも使えるかも…？  

---
### 【無料】デジタル時計【Udon配布】
---
UdonGraph製のデジタル時計！  
とってもシンプルな見た目のサンプルしか付いていませんし、UdonGraphの説明も付属していないのですが、あまり複雑ではないのでUdonの勉強にも使えそうです。  

---
### 【VRChat】AFK時に自動でミュートするOSCツール
---
Windows上で動作するOSCツール！  
AFKに移行した時に、パラメーターの変化を検知して、VRCのマイクをミュートします。  
利用には、OSCが有効になっていることと、AFK検知が有効になっていること、ミュートが切り替え式の設定であることが必要です。  

なお、ソースコードも公開しています。(Windows以外でもご利用いただけるかも?)  

---
### VRCPhysBone-Relocator【無料 / Free】
--- 
Unityのエディタ拡張！  
PhysBoneの"Root Transform"設定を確認して、そのGameObjectの位置にPBコンポーネントを移動させることが出来ます。  

VRM Converter for VRChatでVRoidから変換したアバターなどでよく見られる、「1つのGameObjectに大量のPBコンポーネントが含まれていて、どのコンポーネントがどのボーンと対応するか分からない」ような場合などで役立ちます！  

こちらもソースコードを公開しています。  

---
### [キセテネ for MA【無料】](https://sayamame-beans.booth.pm/items/5057270)
---

情報更新WIP

---

</details>

## 非公開の開発物
---
### Server Controller
---
Minecraftサーバーの起動管理、ホワイトリスト登録等を行うためのPython製のDiscord Botです。  
コマンドを叩くとwolやTCP通信を使用して別PCのMinecraftサーバーを(電源ごと)起動したりします。  
雑に作っちゃったのでソースが公開出来る状態じゃありません。  
公開していないのを良いことに、wolで他のPCも起動出来るようにしています。(管理者限定)
