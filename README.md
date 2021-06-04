# 2021年度生 ゲームプログラミング入門1
- [シラバス](https://drive.google.com/file/d/19wVSBpL08nnUIp8ZX9r5RmHoJM_Z40OZ/)
- [質問](https://meet.google.com/nfe-tjom-mtb)
- [Slack](https://datgm21.slack.com)
- その他
  - [C#書く教科書　記入例](https://github.com/datgm21/csharp-manual)
  - [授業動画](https://github.com/datgm21/gp1/wiki/%E5%BE%A9%E7%BF%92%E7%94%A8%E5%8B%95%E7%94%BB)
  - [VisualStudioのプロジェクトをGitHubにPublishする](https://github.com/datgm21/gp1/wiki/VisualStudio%E3%81%AE%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%82%92GitHub%E3%81%ABPublish%E3%81%99%E3%82%8B)
  - [プロジェクトの更新をGitHubに反映させる](https://github.com/datgm21/gp1/wiki/%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%81%AE%E6%9B%B4%E6%96%B0%E3%82%92GitHub%E3%81%AB%E5%8F%8D%E6%98%A0%E3%81%95%E3%81%9B%E3%82%8B)
  - [昨年度の講義資料](https://github.com/datgm20/gp1)

## 参考URL
- [Unity Learning Materials](https://learning.unity3d.jp/)
- [UNITYのインストール手順](https://am1.games/tutorials/unity/install/)
- [Unity入門の森　ゲームの作り方.](https://3dunity.org/game-create-lesson/)
- [Paizaラーニング C#](https://paiza.jp/works/cs/primer)
- [ドットインストール Unity入門](https://dotinstall.com/lessons/basic_unity_v2)
- [Unityスタッフのブックマーク](https://note.com/unityjapan/m/m5978b902c2b5)
- [GmailアカウントとGitHubアカウントを作成していない場合はこちら](https://docs.google.com/document/d/16MW6maMYvt8m-60RM5wU_LzJ5r-3Hm0WTnxoBGDzxIA/)
- [ハーバード大学 CS50 の日本語版翻訳プロジェクトのページ](https://cs50.jp/)
- [Unityでのモノの動かし方](https://docs.google.com/document/d/1Su0trfKxB2iLfGdxt1s7pJr76NFwqwdw-pbDhaCrtvE/)

# 7回目
## 前回の課題の結果(18名中)
- ボーナス含めてパーフェクト 1名
- 斜め移動ボーナス 3名
- 問題なし 6名
- 軽微なミス 1名

---

- int.Parse()未使用 2名
- 時間オーバー、提出ミス 5名

## 予定
- 変数の続きから
  - [GP1-07 変数2](https://youtu.be/smKALzN0Gus?t=2600)

## 時間があれば
- [GP1-05:Unity ボタン](https://youtu.be/aP56UZ953Hg)
- バランスブレイカーの画面をVisual C#で作成する

# 6回目
## 復習問題
- Visual C#の新規プロジェクトを作成して、名前をfukuv0603にする
- [VisualStudioのプロジェクトをGitHubにPublishする](https://github.com/datgm20/gp1/wiki/VisualStudio%E3%81%AE%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%82%92GitHub%E3%81%ABPublish%E3%81%99%E3%82%8B)
- フォームに以下を設置
  - ラベル(Label)を1つ
  - テキストボックス(TextBox)を2つ置いて、どちらのTextも1を設定
  - タイマー(Timer)を1つ
- タイマーに以下のプログラムを書く
  - 一方のテキストボックスの値をint型に変換して、ラベルのLeftに足す
  - もう一方のテキストボックスの値をint型に変換して、ラベルのTopに足す
- タイマーが動くように設定する
- できたらコミットして、Pushする

### 上記ができた人向けのボーナス課題
- ボタンを4つ、十字に配置して、ボタンを押したらその方向にラベルの移動方向が変わるようにする
- できたらコミットして、Pushする

## 内容
- 07.md 変数～動的なプログラム～ からをUnityで
  - [GP1-06 変数](https://youtu.be/z8KlJWFuskc)
  - [GP1-07 変数(2)](https://youtu.be/smKALzN0Gus)

# 5回目

## 話題
- [ハーバード大学 CS50 の日本語版翻訳プロジェクトのページ](https://cs50.jp/)

## 復習問題
- Visual C#の新規プロジェクトを作成して、名前をfukuv0527にする
- [VisualStudioのプロジェクトをGitHubにPublishする](https://github.com/datgm20/gp1/wiki/VisualStudio%E3%81%AE%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%82%92GitHub%E3%81%ABPublish%E3%81%99%E3%82%8B)
- 以下のものを作る
  - ラベル(Label)を1つ
  - ボタン(Button)を4つ作って十字に配置
  - ボタンを押した方向にラベルが動くようにする
- できたらコミットして、Pushする
- さらに、プログラムコードのスクリーンショットをSlackの自分のチャンネルに貼り付ける
  - スクリーンショット：　ウィンドウズキー + Shift + S キーを押して、スクリーンショットを取りたい範囲をマウスでドラッグで選択
![image](https://github.com/datgm21/gp1/blob/main/image.png?raw=true)


## 内容
- [GP1-05:VisualC# コントロール(Control)～表現を増やす～](https://youtu.be/MAie5pHmFyg)

## 演習6-1, 6-2のマークダウン

```md
## 演習6-1
TextBoxを2つ、Labelを1つ、ボタンを1つ作って、ボタンの表示を「演習6-1」に変更する。
ボタンを押したら、2つのTextBoxの内容を足して、Labelに表示するプログラムを作ってみよう。

## 演習6-2
以下を試してみよう。

- TimerのIntervalを変更する
- 足す値を変更する
- Topにも値を足す
```

## 時間があれば
- [GP1-05:Unity 移動](https://youtu.be/hnsH9L5ZBD8)
  - [Unityでのモノの動かし方](https://docs.google.com/document/d/1Su0trfKxB2iLfGdxt1s7pJr76NFwqwdw-pbDhaCrtvE/)


# 4回目
## 話題
- [Christoph Molnar. 説明可能なAI](https://hacarus.github.io/interpretable-ml-book-ja/)

## 前回のミスのポイント
- GitHubにサインイン
- 前回提出した`ensyu0513`リポジトリーをクリックして選択
- 以下を確認
  - 左上の自分のアカウントの左のアイコンが鍵になっていたらPrivate設定なので提出ミス
    - GitHub DesktopからPublishするときにPrivateを外していない
    - せっかく提出してもこちらで確認できない
  - ファイルの一覧を見て、プロジェクトフォルダーや`ensyu0513.sln`ファイルがない
    - GitHutに登録するフォルダー間違い
    - 場所の指定でプロジェクト名を削除しなかったか、単純にフォルダーの指定間違い
    - ソリューションファイルがないので後で開くのが面倒

## 復習
- Visual C#の新規プロジェクトを作成して、名前を`fukuv0520`にする
- GitHubにPublishする
- ボタンを3つ配置する
- それぞれのボタンに、押すと何かを表示したり、動いたり、消えたりする機能を実装する。ただし、前回の演習とは動作を変更すること
- プロジェクトの更新をGitHubに反映させる
- 以上完了したらプログラムを実行して、以下の4枚のスクリーンショットをSlackの自分のtimesチャンネルに貼り付けてください
  1. ボタンを押す前
  2. 1つ目のボタンを押した時
  3. 2つ目のボタンを押した時
  4. 3つ目のボタン

※スクリーンショット：　ウィンドウズキー + Shift + S キーを押して、スクリーンショットを取りたい範囲をマウスでドラッグで選択

## 内容
- [GP1-04:VisualC# データの型、計算](https://youtu.be/Gum71fCVsb4)


# 3回目
## 準備
- GitHubを開く > Sign in > csharp-manual を開く
- 03.mdをクリックして開く

## 復習
- Visual C#の新規プロジェクトを`fukuv0513`という名前で作成する
- ボタンを1つ配置する
- ボタンの表示を`button1`から`復習`に変更
- ボタンをクリックしたら「前回の復習です」とMessageBoxで表示させる

以上実装が完了したら、実行して、ボタンを押して、メッセージが表示されている画面のスクリーンショットを撮って、Slackの自分のチャンネルに貼り付けてください。

## 内容
- `v0513`という名前で新しいプロジェクトを作成
- [VisualStudioのプロジェクトをGitHubにPublishする](https://github.com/datgm21/gp1/wiki/VisualStudio%E3%81%AE%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%82%92GitHub%E3%81%ABPublish%E3%81%99%E3%82%8B)
- [手順動画 Visual C#](https://youtu.be/BVRWsai9NOw)
- [プロジェクトの更新をGitHubに反映させる](https://github.com/datgm21/gp1/wiki/%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%81%AE%E6%9B%B4%E6%96%B0%E3%82%92GitHub%E3%81%AB%E5%8F%8D%E6%98%A0%E3%81%95%E3%81%9B%E3%82%8B)


# 2回目
## 話題
- [Unity入門の森　ゲームの作り方.](https://3dunity.org/game-create-lesson/)

## 内容
- [手順動画](https://youtu.be/lTNRVO3PPhE)
- [書く教科書のオリジナルリポジトリー](https://github.com/tanakaedu/csharp-manual)

## GW中の自習
- e-typing
- [UNITYのインストール手順](https://am1.games/tutorials/unity/install/)
- [Unity入門の森　ゲームの作り方.](https://3dunity.org/game-create-lesson/)
- [Paizaラーニング C#](https://paiza.jp/works/cs/primer)

## 演習
講義で自分で作成した教科書を参考にして、以下のプログラムを作成してください。

- プロジェクト名を ensyu0429 とする
- ボタンを１つ配置して、ボタンのテキストを`自己紹介`にする
- 自己紹介 ボタンを押したら、自分の名前を`MessageBox`で表示する
- 以上できたら、実行画面のスクリーンショットを撮って、Slackの自分の活動チャンネル(#times_名前)にCtrl+Vで貼り付ける
  - 作成したプログラムを実行して、ボタンを押して、メッセージボックスを表示しておく
  - ウィンドウズキー+Shift+Sキーを押したら、スクリーンショットを取りたい範囲をマウスでドラッグで選択
  - [Slack](https://datgm21.slack.com)を開く
  - チャンネルを追加する を押して、`times_名前` を入力して作成する。説明とプライベート設定は不要
  - 作成した自分用のチャンネルを選択
  - コメントのところをクリックして選択したら、Ctrl+Vキーでスクリーンショットを貼り付ける
  - 右下の送信ボタンでメッセージを送信する



# 1回目
- ガイダンス
  - [プログラミングを学ぶ前に](https://docs.google.com/presentation/d/1mIIrnua1nf2yCiXA6KMkTUOylzPIxiUCeqQEdtHdPhc/)
  - [講義メモ](https://docs.google.com/document/d/1PzCptqOYNbmJr5D2VCR3ppziEdcZzHMJEJWUKX4GTGA/)
    - Visual C# / Unity
  - 独習
    - [Unity Learning Materials](https://learning.unity3d.jp/)
    - [Paizaラーニング C#](https://paiza.jp/works/cs/primer)
      - アカウントをGitHubで登録
    - [ドットインストール Unity入門](https://dotinstall.com/lessons/basic_unity_v2)
    - [UNITYの準備](https://am1.jp/unity/getting-started/)
    - この1年でUnity関連の良質な記事が増えたのでよいページを探してみてください！

