<p align="center">
  <img src="./assets/Elixir-icon.png" alt="Elixir Browser Logo" width="256"/>
</p>

<p align="center">
  <a href="https://github.com/SF-FLAM/ElixirBrowser/releases"><img src="https://img.shields.io/badge/Download-Releases-brightgreen?style=for-the-badge"></a>
  <a href="https://github.com/sponsors/SF-FLAM"><img src="https://img.shields.io/badge/GitHub-Sponsor-EA4AAA?style=for-the-badge&logo=githubsponsors"></a>
  <a href="https://buymeacoffee.com/sf_flam"><img src="https://img.shields.io/badge/Buy_Me_A_Coffee-FFDD00?style=for-the-badge&logo=buymeacoffee&logoColor=black"></a>
</p>

# Elixir Browser

> **[English](README.md) | [日本語 (Japanese)](README.ja.md)**

<br>

ElixirはChromiumベースの拡張機能対応ブラウザです。  
Kiwi Browserにインスパイアされ、拡張機能サポートと、独自のUI改善、非効率な挙動の変更を目的としています。  
  
ただし、Kiwiの開発者およびチームとは一切関係はありません。  
本プロジェクトはChromium公式ソースから独自にフォークしたものであり、既存の他ブラウザ（Kiwi等）からのソースコードやバイナリの流用も行っていません。  
  
また、殆どのGoogle依存機能を排除し、同時に不要な通信を遮断しています。  
翻訳機能や検索候補の表示など、利便性に強く関わる部分はユーザーが任意で切り替え可能です。

<br>

<p align="center">
  <img src="./assets/Screenshot_0_Elixir_Browser.png" alt="screenshot0" width="32%">
  <img src="./assets/Screenshot_1_Elixir_Browser.png" alt="screenshot1" width="32%">
  <img src="./assets/Screenshot_2_Elixir_Browser.png" alt="screenshot2" width="32%">
</p>

<br>

## 主な機能

*   **拡張機能サポート**
    * Chromeウェブストアから、デスクトップ版Chromeと同じ拡張機能をインストールして使用できます。

*   **強化されたUI**:
    *   **常時表示タブバーオプション**
    *   **下部ツールバーオプション**
    *   **不要なUIの削除**
    *   **翻訳ボタンをメニューに追加**
    *   **独自のスピードダイアルの実装**
    *   **etc...**

*   **ジェスチャー機能の実装**:
    *   複数のアクションを自由に登録可能。快適なブラウジングを実現します。

*   **一部挙動の変更**:
    *   **戻る履歴が無いタブで戻るジェスチャーを行った場合、ホームに戻らずタブを閉じる**
    *   **etc...**

*   **プライバシー保護**:
    * オリジナルのChromiumに存在する複数の情報送信を遮断しています。

*   **継続した長期開発**:
    * 定期的に最新のChromiumバージョンに追従し、可能な限り保守を行います。

<br>

## 支援 & 宣誓

Elixir Browserは個人によって開発されているプロジェクトです。  
**完全に非営利であり、開発者は当アプリにおいて、アフェリエイト、個人情報収集、課金コンテンツの搭載等による一切の収益化を行っておらず、また今後も恒久的に行わない事を誓います。**  

ただし、個人的な支援は大歓迎です🤑  
  
Chromiumの改変とその保守は非常に過酷な作業です。  
正直めちゃ大変なので、長期的な継続の為、どうか応援のほどよろしくお願い致します(貧民)  
↓↓↓
  
<<**[❤️ GitHub Sponsors](https://github.com/sponsors/SF-FLAM)**>>

<<**[☕ Buy Me A Coffee](https://buymeacoffee.com/sf_flam)**>>  

<br>

## ダウンロード

APKは以下のリンクからダウンロードできます。  


<<**[Releases](https://github.com/SF-FLAM/ElixirBrowser/releases)**>>


<br>

## 開発履歴 ＆ 今後実装予定の機能

詳細な開発の履歴に加えて、今後実装するかもしれない機能について記載しています。  
基本的にKiwiの代替として自分用に作ったものなので、機能の取捨選択もそのような傾向があります。  
  
**改変、新規追加したファイルは"改変ファイル一覧"に記載されているものが全てであり、それ以外は全て素のChromiumです。**  

なお、Googleへの不要な通信は概ね機能自体を根本から削除しています。  
プライバシー保護重視というよりは、軽量化の結果そうなったという感じです。  
その為、削除するとブラウジングそのものに影響が出そうな機能は幾つか残っています。これは、今後のアップデートで慎重にテストを重ねて削除を進めていく予定です。  
  
<<**[History](./CHANGELOG.ja.md)**>>

<br>

## 不具合報告

何か問題を見つけた場合は、GitHubの Issues までお寄せください。可能な限り改善に努めます。多分。  

<<**[Issues](https://github.com/SF-FLAM/ElixirBrowser/issues)**>>

<br>

## Q & A

Q： **このブラウザは日常的に使用するのに十分な安定性がありますか？**  
A：個人的にElixirをメインブラウザとして毎日使用しており、その安定性に満足していますが、皆にとってもそうとは限りません。  
これは個人プロジェクトである為、アップデートには重大なバグ、クラッシュ、または機能の不具合が含まれる場合があります。  
特に、私の端末では発生しないバグは見落とされがちです。このブラウザは開発途中のものであることを理解した上で、自己責任でご利用ください。  
<br>
Q : **対応している動作環境は？**  
A：Chromiumの基本仕様に準拠しています。現在はAndroid 10以降（ARM64）が必要です。32ビット版は提供されていません。  
ただし、私自身の端末でしかテストできないため、確実な互換性は保証できないことをご了承ください。  
<br>
Q : **どうしてオープンソースじゃないの？中身見せろ！**  
A : 将来的にはOSS化を目指しています。現時点ではコメントを全て日本語で書いているので、公開するなら英語に直したい所です。  
アップデートの方を優先しており、コードの管理まで手が回らないので、ゆっくり進めていこうと思います。 
ただし、プロジェクトを終了することになった場合は、仮にコードがまだ整理されていなくても全て公開します。  
<br>
Q : **パスワードマネージャは無いの？**  
A : ありません。Androidの本体設定で指定されているパスワードマネージャを使うようになっています。  
標準だとGoogleパスワードマネージャが使われていると思いますが、AndroidのバージョンによってはKiwiやElixirなどの非大手ブラウザで警告が出るようです。パスワード入力自体は問題無く出来ます。  
個人的にはBitwarden(拡張機能ではなくアプリの方)の使用を推奨しています。こちらだとパスキーも問題なく使える事が確認出来ています。  

