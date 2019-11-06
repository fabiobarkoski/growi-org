---
home: true
heroText: 快適な Markdown Wiki を<strong>*無料で*</strong>
heroImage: /assets/images/banner-logo.png
heroButtons:
- text: 機能紹介
  link: /ja/#features
- text: デモサイト
  link: https://demo.growi.org
- text: GROWI.cloud
  link: /ja/#cloud
sections:
  features:
    title: 機能紹介
  documents:
    title: ドキュメント
  cloud:
    title: GROWI.cloud
    descriptions:
      text: 『Markdown × Wiki × 自由。』
      subtext: 情報共有をもっと身近に、もっと手軽に
      subsubtext: GROWI.cloud は GROWI を手軽に始められるクラウドサービスです
      button_text: GROWI.cloud を始める
  joinus:
    title: JOIN US
    descriptions:
    - GROWI は、<a href="https://weseek.co.jp">WESEEK, Inc.</a> が開発を行い、<br> MITライセンスで公開しているオープンソースソフトウェアです。
    - 開発を手伝っていただけるコントリビューター、開発してみたいインターン生を募集しています。<br> まずは Slack に参加し、気軽にWESEEKメンバーに声をかけてください。
  contact_us:
    address: 東京都新宿区西早稲田2-20-15 高田馬場アクセス10F
    tel:
      text: 03-6667-4862
      link: 0366674862
    email: info@weseek.co.jp
features:
- image_path: /assets/images/screenshots/editor.png
  details:
  - title: Markdown
    icon: pencil
    description: 左右2画面でのリアルタイムプレビューが可能。言語ごとのコードハイライトや絵文字や注釈(footnotes)、タスクリスト、Bootstrap による HTML コードにも対応しています。
  - title: シンプルなアセット管理
    icon: picture
    description: ファイルのアップロードは編集画面にファイルをドロップするだけです。ストレージはローカルFSと AWS S3 のどちらかを選択できます。
- image_path: /assets/images/screenshots/keymap.png
  details:
  - title: 3種のキーマップ
    icon: keyboard
    description: Vim/Emacs/Sublime Text のキーマップをサポート。ブラウザからでも快適に入力できます。
  - title: 絵文字入力
    icon: smile
    description: <a href="https://www.emojione.com/emoji/v3">EmojiOne v3</a> による絵文字が文書を表情豊かに彩ります。入力支援機能として、<code>:</code>から入力を始めることでオートコンプリートウィンドウを表示します。
- image_path: /assets/images/screenshots/customize.png
  details:
  - title: テーマの変更
    icon: music-note
    description: 管理画面からサイトのテーマとコードハイライトのテーマの変更が可能です。 <br/> それぞれにライトテーマ、ダークテーマを複数種類用意しています。
  - title: チームに合わせたカスタマイズ
    icon: cog
    description: 挙動・レイアウトを2タイプから選択できる他、Markdown レンダリング設定を管理画面から変更できます。チームの使い方に合わせた柔軟な設定が可能です。
- image_path: /assets/images/screenshots/search.png
  details:
  - title: 高速な検索
    icon: magnifier
    description: ElasticSearch を利用したページタイトルのインクリメンタルサーチと、ページコンテンツの全文検索が可能です。日本語ユーザーにもやさしく、英数字は全角半角どちらでもヒットするようになっています。
- image_path: /assets/images/screenshots/ldaplogin.png
  details:
  - title: 強力な認証機構・グループ管理
    icon: lock
    description: <a href="http://www.passportjs.org/">Passport</a>による認証機構を採用、LDAP 認証および OAuth プロバイダを利用したログインをサポートしています。<br /> また、v3.0 からはグループごとのアクセスコントロールを搭載し、より柔軟なページ管理が可能になりました。
  - title: オープンWiki
    icon: users
    description: ゲストユーザーに対して閲覧を許可することで、オープンWikiの公開も可能です。
- image_path: /assets/images/screenshots/comment.png
  details:
  - title: コメント機能でコミュニケーション活性化
    icon: bubble
    description: ページ毎にコメントをスレッド表示できます。もちろんコメントも Markdown による記述・プレビュー、ファイル添付が可能。<span class="text-muted">(コメント追加時の Slack 通知には近々対応予定
---