## これは何
+ Firefox 拡張 [Scalper Manager](https://addons.mozilla.org/ja/firefox/addon/scalper-manager/) でエクスポートした以下のファイルです。
 + json 形式の転売セラーブラックリスト
 + csv 形式の転売セラーブラックリスト ( [アマゾン転売屋ブラックリスト・ブックマークレット](https://note.com/jackpot_hide/n/n228b0876673d)準拠 )
 + json 形式の違法セラーデータ ( ソフトウェア処理向き )
 + csv 形式の違法セラーデータ ( 表計算ソフトウェア処理向き )

## リストの著作権
+ 著作権法に定められたデータベースの著作物には相当しないと思われるため、著作者はパブリックドメインだと考えています。ですから自由にあなたの Firefox 拡張 [Scalper Manager](https://addons.mozilla.org/ja/firefox/addon/scalper-manager/) にインポートしてご利用ください。

## 更新情報
+ 2021/08/27 : 他の方が作成されたリストの取り込みをやめました。
+ 2021/08/29 : 違法セラーデータの公開を始めました

## 公開者によるメンテナンス基準
+ 転売セラーとして登録されてしまったセラーの削除は行いません

## 公開者によるセラー追加基準
+ 違法行為を現在行っているあるいは過去に行っていたセラー
+ 景品表示法等法規に触法しているセラー
+ リスト作成者の購買行動の邪魔になっているセラー
+ 定価＋税を超える金額を販売価格としているセラー

## 関連ソフトウェア
+ [アマゾン転売屋ブラックリスト・ブックマークレット](https://note.com/jackpot_hide/n/n228b0876673d)
+ [転売屋ブラックリストツール - Chrome ウェブストア](https://chrome.google.com/webstore/detail/%E8%BB%A2%E5%A3%B2%E5%B1%8B%E3%83%96%E3%83%A9%E3%83%83%E3%82%AF%E3%83%AA%E3%82%B9%E3%83%88%E3%83%84%E3%83%BC%E3%83%AB/hfehbkmogocbghcbdenpjooehooppmjh?hl=ja)
+ Firefox 拡張 [Scalper Manager](https://addons.mozilla.org/ja/firefox/addon/scalper-manager/)
+ [mitsugu/Scalper: 秀さん作のアマゾン転売屋ブラックリストのブックマークレット版とGoogle Chrome拡張版を Firefox 用に最適化を行った拡張 Scalper Manager のソースです。](https://github.com/mitsugu/Scalper)
+ [mitsugu/changeseller](https://github.com/mitsugu/changeseller)
+ [アマゾン転売屋ブラックリスト json データインポートブックマークレット](https://gist.github.com/mitsugu/ac37f886d84d605ab0c34ca02703179b)

## Q and A
Q. どうやって使えばいいのでしょうか？  
A. [Scalper Manager](https://addons.mozilla.org/ja/firefox/addon/scalper-manager/) のオプションページにテキストボックスがありますのでコピペして RESTORE Scalper List ボタン(データを置き換える場合)もしくは Merge Other Scalper List ボタン(データを追加統合する場合)を押してください。

Q. [アマゾン転売屋ブラックリスト・ブックマークレット](https://note.com/jackpot_hide/n/n228b0876673d)とデータを共有できますか？  
A. できます。オプションページのテキストボックスにブックマークレットでエクスポートした csv ファイルの中身をコピー・アンド・ペーストし、RESTORE Scalper List ボタン(データを置き換える場合)もしくは Merge Other Scalper List ボタン(データを追加統合する場合)を押してください。

Q. Scalper Manager でエクスポートした json データを[アマゾン転売屋ブラックリスト・ブックマークレット](https://note.com/jackpot_hide/n/n228b0876673d)と共有したいのですが。  
A. [アマゾン転売屋ブラックリスト json データインポートブックマークレット](https://gist.github.com/mitsugu/ac37f886d84d605ab0c34ca02703179b)を公開しているのでご利用ください。

Q. ある日突然、転売セラーの目印が表示されなくなりました。  
A. Firefox のストレージ管理の仕様によりストレージがクリアされてしまうことがあります。その際は面倒ですがバックアップしていたファイルを再度オプションページからリストアしてください。

Q. 転売セラーブラックリストをリストアしたらそれまでにダブルクリック入力した転売セラーの目印が消えてしまったのですが。  
A. Scalper Manager のリストア機能はバックアップのリストアです。リストアなので当然拡張内のデータはバックアップ実行時点まで巻き戻ります。

Q. 明らかに高額転売屋と思われるセラーがデータとして登録されていないようですが。  
A. Firefox Addon [Scalper Manager](https://addons.mozilla.org/ja/firefox/addon/scalper-manager/) は各ユーザがご自身でデータを登録すること前提として作られています。なので高額転売セラーを発見した場合はご自身で登録してください。もちろん他の方がエクスポートした json データをオプションページよりマージすることもできます。

Q. このリポジトリの転売セラーブラックリストのファイル名には年月日が含まれていません。リストがいつ作られたものか知りたいのですが。  
A. このリポジトリのコミット・ログの日時を見てください。

