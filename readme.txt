■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■
■tomcat6.0 eclipse4.3 hello workd 開発手順
https://webref.eomec.com/css-demo-fonts/google-fonts-libre-barcode-128-text

https://searchman.info/java_eclipse/1100.html
①
D:\eclipse4.3\pleiades\eclipse\eclipse.exeを起動する

workspace:D:\Git\tomcat_test
②ファイル→新規→プロジェクト...→Web→動的 Web プロジェクト→
	プロジェクト名：	tomcat_test
	[V]デフォルト・ロケーションを使用
	ターゲット・ランタイム
		新規ランタイム...→
			Apache Tomcat v6.0
			[V]新規ローカル・サーバー作成
				次へ
				名前：	Apache Tomcat v6.0
				Tomcatのインストール・ディレクトリー：	D:\eclipse4.3\pleiades\tomcat\6
				JRE：	java6
				完了
		Apache Tomcat v6.0
	動的webモジュールバージョン:	2.4
	構成：	Apache Tomcat v6.0デフォルト構成
	EAR	無効
	ワーキング・セット	[ ]
	次へ
	次へ
	完了
	[popupあれば、YESを押す]


	プロジェクト・エクスプローラー
	tomcat_test
	Javaリソース
		src
	右クリック→新規→クラス
		パッケージ：info.searchman
		名前：HelloWorld



http://localhost:8080/tomcat_test/servlet/hello

		Apache Tomcat v6.0
