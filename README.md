# NEO-SkyColors



## 名称
NEO-SkyColors

## 説明
こちらのソフトウェアは、旧自作サイトで公開していたN-SCF(Web版)を再作成し、GitLab Pagesで公開できるように調節したものです。

## バッジ
On some READMEs, you may see small images that convey metadata, such as whether or not all the tests are passing for the project. You can use Shields to add some to your README. Many services also have instructions for adding a badge.

## 外観
UIデザインやカラーリングに関しては、メインサイト側と同様にしています。<br />
Depending on what you are making, it can be a good idea to include screenshots or even a video (you'll frequently see GIFs rather than actual videos). Tools like ttygif can help, but check out Asciinema for a more sophisticated method.

## インストール方法
開発者の方は、こちらのファイルをダウンロードして、```SkyColors```のファイル内で
```
dotnet watch run --pathbase=/skycolors
```
をコマンドラインで実行し、好みのブラウザで```http://localhost:5204/skycolors```にアクセスすると利用できます。<br />
(前提条件としてdotnetのインストールが必要です。)<br />
詳しくはMicrosoft公式のBlazor wasmのページなどをご覧ください。
<details>
<summary>ページ更新方法</summary>
・bin/obj/outputディレクトリをすべて削除<br />
・コマンドラインでdotnet publish -c Release -o outputを実行<br />
・(gitlab-runner registerでCI/CDを設定し、gitlab-runner runで接続)<br />
・コミットし、プルする<br />
</details>

## 利用方法
[リンク](https://lemon73.gitlab.io/skycolors)にアクセスすることで、そのままWebで利用できます。<br />
(現時点ではメイン機能であるランダムカラー機能が搭載されていないので、詳しい利用方法については省略します。)

## サポート
Tell people where they can go to for help. It can be any combination of an issue tracker, a chat room, an email address, etc.

## ロードマップ
##### 今後実装予定の内容
- ランダムカラーシステム(メイン機能)
- 国際化(i18n)
- PWA対応

## 貢献
現時点では寄付を受け入れていませんが、将来的には寄付を受け付ける可能性が高いです。受け入れの条件に関しては、その際に決定します。

For people who want to make changes to your project, it's helpful to have some documentation on how to get started. Perhaps there is a script that they should run or some environment variables that they need to set. Make these steps explicit. These instructions could also be useful to your future self.

You can also document commands to lint the code or run tests. These steps help to ensure high code quality and reduce the likelihood that the changes inadvertently break something. Having instructions for running tests is especially helpful if it requires external setup, such as starting a Selenium server for testing in a browser.

## 著者と謝辞
##### 著者
- Lemon73
##### 謝辞
C#やBlazorの開発関係者、UI部分のBootstrap開発関係者、またそれらの情報提供者、その他開発に関係した多くの人に感謝の意を示します。

## ライセンス
プログラム:GPL v3<br />
緩和する可能性もあります。

## プロジェクトの状態
開発中です。
