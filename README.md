# サンプルアプリ(完成版)
* UnityでmBaaSのスクリプトおよびデータストア機能を用いてガチャ機能を実装したアプリの完成版です
## 遊び方
* 各手順の詳しい解説は、[チュートリアル ドキュメント](https://goo.gl/3jcafs)をご参照ください
1. UnityプロジェクトおよびNode.jsファイルを以下のリンクよりダウンロードします
    + [ダウンロード(zip)](https://github.com/NIFTYCloud-mbaas/UnityScriptApp/archive/release/20170727.zip)
1. Unityでの設定
    1. ダウンロードしたzipフォルダを解凍し、"UnityScriptApp"フォルダ内の"UnityProject"をUnityで開きます
    1. gachaシーンを開きます
    1. `NCMBSettings`オブジェクトのInspectorを開き、ご自身のアプリのAPIキー２つを入力します
1. スクリプト ファイルの編集
    1. "UnityScriptApp\Node.js\gacha.js"を開きます
    1. `アプリケーション キー`(10行目)，`クライアント キー`(11行目)をそれぞれご自身のアプリのキーに書き換えます
    1. gacha.jsをスクリプト管理画面からアップロードします
        * メソッド: GET
        * ファイルの状態: 実行可能
1. データストア操作
    1. データストア管理画面を開きます
    1. "UnityScriptApp\GachaItems.json"をインポートします
    1. ご自身でお好きなガチャアイテムを追加することもできます
1. Unityで`再生ボタン`をクリックすればアプリで遊ぶことができます