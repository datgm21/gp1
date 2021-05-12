# UnityのプロジェクトをGitで管理するように設定して、GitHubにPublishする手順

- Unityでプロジェクトを作成しておく
- [Ctrl]+[S]キーでシーンを保存
- [File]メニューから[Save Project]を選択して、プロジェクトを保存
- **GitHub Desktop** を起動する
- *File*メニューから、*Options*をクリック
- GitHub.comがサインイン済みの時は、*Sign out*をクリックする
- *Sign in* ボタンをクリックして、Edgeが開いたらURLをコピーして、Chromeに貼り付けて、GitHub Desktopで開く でサインイン
- *File*メニューから*New Repository*(リポジトリー)
- *Local path*の*Choose*ボタンをクリック
- *ドキュメント* > *名前のフォルダー* から、登録したいUnityのプロジェクトフォルダーをクリックして、フォルダーの選択をクリック
- *Local path*の最後のフォルダー名を選択して、切り取って、*Name*欄に貼り付け
- *Initialize this repository with a README* にチェック
- *Git ignore*欄をクリックして、`un`と入力すると*Unity*が選択されるのでクリックなどして選択
- *Create repository*ボタンをクリック
- 右上の*Publish repository*ボタンをクリック
- *Keep this code private* はチェックしたままにする
- *Publish repository*ボタンをクリック

## 共有設定
そのままだと教員やチームメンバーから参照できないので、以下の手順でリポジトリーにメンバーを追加する。

- Google Chromeシークレットモードを開く
- github.com を開く
- サインインする
- 作成したリポジトリーを開く
- 右の方にある歯車アイコンの*Settings*をクリック
- 左の方にある*Manage access*をクリック
- GitHubのパスワードを入力
- 緑色の*Invite teams or people*ボタンをクリック
- 追加するメンバーのアカウントやメールアドレスを入力すると、候補のアカウントが表示されるので該当するものをクリックして選択
- *Write*を選択して、*Add*から始まる緑色のボタンをクリック

以上で設定完了。しばらく待つと、登録されたメンバーのGitHubをWebページの右上のベルマークのところに
`Invitation to join ????? from ??????`というメッセージが届くので、クリックして開いて、緑色の**Accept invitation**ボタンをクリックすることでリポジトリーに参加できる。


# 変更したものを反映させる手順
- Unityの*File*メニューをクリックして、*Save Scenes*を選択してシーンを保存する
- *File*メニューをクリックして、*Save Proejct*を選択してプロジェクトを保存する
- GitHub Desktopに切り替える
- *Changes*タブをクリック
- *Summary*欄に変更した内容を書く(ボタンの追加、完成など)
- *Commit to master*ボタンをクリック
- 右上の*Push origin*ボタンをクリック

