------------------------------------------------------------
■サンプルアプリケーション セットアップ手順
------------------------------------------------------------

【1. 事前条件】

以下のソフトウェアを事前にセットアップしてください。

(1) JDK6.0
(2) Tomcat7.0.x
(3) PostgreSQL 9.2.x


【2. データベースのセットアップ】

(1) PostgreSQL上に、以下のデータベースを作成してください。

　データベース名 : ensdemo
　ユーザ名       : postgres
　パスワード     : postgres

※サンプルアプリケーションであるため、postgresユーザを利用しています。
　別のデータベース名や認証情報を利用する場合は
　demo.warを解凍して、中に含まれるWEB-INF/classes/jdbc.diconを修正したうえで
　zipファイルとして再圧縮して拡張子を.warに変更してください。


(2) pgAdmin等を利用して本ドキュメントと同じディレクトリにある
　　demo.sqlを上で作成したデータベースに対して実行してください。

以上でデータベースのセットアップは完了です。


【3. アプリケーションのデプロイ】

(1) 本ドキュメントと同じディレクトリにある demo.war を
　　Tomcatのwebappsディレクトリに配置してください。


以上で事前セットアップは完了です。
