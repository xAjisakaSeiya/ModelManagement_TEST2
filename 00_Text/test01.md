* JUKI環境における作業
* 基本Oracleインストール
  * 注意
    * バージョンアップ後にダンプをエクスポート
    * 新規インストール時にテンプレートコピー
    * インストールするOracleのバージョンが12cなので、使用するユーザを確認
      * いなければ仮想ユーザ
      * この場合、複数インスタンス作成するときはアクセス権の修正
      * C:\Oracle\product\11.2.0\dbhome_1\databaseに対して、アクセス権を付与、下位ディレクトリに伝搬
    * メモリはマシンに応じて変更
      * SGAが2GB以上の場合は、初期値のSGA_MAX_SIZEを変更
    * キャラセットもおそらくSJISに
    * 記憶域
      * IDATAを大型に
      * AUTOEXTENDにチェック、メモリ量を10MBに
      * 他は適宜

    
