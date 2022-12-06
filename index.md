# WMSマニュアル

## ドキュメント作成者
仲井暉人

## 改訂履歴
-1.0:
  - 作成日時：2022-12-08
  - 更新内容：初版作成

## 目次

- 各画面操作方法
  - [WMSインストール方法](#4-wmsインストール方法)
  - [ログイン方法](#5-ログイン方法)
  - [入荷](ItemPO.md)
    - [入荷予定一括入荷処理](/ItemPO.md#s19-入荷予定一括入荷処理)
    - [入荷予定一覧](/ItemPO.md#s22-入荷予定一覧)
  - [出荷](Ship.md)
    - [出荷グループ作成](/Ship.md#n10-出荷グループ作成)
    - [出荷帳票作成](/Ship.md#n15-出荷帳票作成)
    - [出荷作業中取消](/Ship.md#出荷作業中を取り消したい場合j40-ec受注一括更新)
    - [荷札データ出力](/Ship.md#w13-荷札データ出力)
    - [問い合わせ番号取り込み](/Ship.md#w40-各種データ取り込み問い合わせ番号)
    - [出荷確定](/Ship.md#w50-出荷確定)
    - [出荷確定取消](/Ship.md#出荷確定を解除したい場合j35→w30-出荷確定解除)
    - [ダッシュボード](/Ship.md#z10-ダッシュボード)
  - [受注](ECOrder.md)
    - [受注一覧](/ECOrder.md#j35-ec受注一覧-オーダー別)
    - [受注伝票別](ECOrder.md#j33-ec受注一覧-伝票別)
    - [返品登録](ECOrder.md#j14-ec受注登録返品登録)
  - [倉庫業務](Warehouse.md)
    - [在庫ロケーション一覧](Warehouse.md#w70-在庫ロケーション一覧)
    - [時点在庫集計](Warehouse.md#w72-時点在庫集計)
    - [僅少在庫リスト](Warehouse.md#w74-僅少在庫リスト)
    - [出荷実績集計](Warehouse.md#w80-出荷実績集計)
    - [入荷実績集計](Warehouse.md#w82-入荷実績集計)
    - [ロケーションマスタ](Warehouse.md#w90-ロケーションマスタ)
    - [商品在庫調整](Warehouse.md#s80-商品在庫調整)
    - [商品在庫調整一覧](Warehouse.md#s81-商品在庫調整一覧)


## 4. WMSインストール方法

1. **※※※重要**　WMSの[URL](https://stockcrewbaw.azurewebsites.net/?cd=wego)を**Microsoft Edge**に入力する　**※※※**(https://stockcrewbaw.azurewebsites.net/?cd=wego)
2. 下記画面が表示されるので[詳細情報]をクリックする
   1. ![BAWのWindows保護画面](/img/Install/BAW_Windows_Guard.png)
3. 下記画面が表示されるので[実行]をクリックする
   1. ![BAWのWindows保護詳細画面](/img/Install/BAW_Windows_Guard_Dtl.png)
4. WMSが開くので認証キーを入力する(初回のみ、K6wj43を入力)
   1. ![認証キー入力画面](/img/Install/Insert_SystemKey.png)

## 5. ログイン方法
1.   WMSのURLを**Microsoft Edge**に入力する(https://stockcrewbaw.azurewebsites.net/?cd=wego)
2.   ログイン画面が開くので社員コードに100, パスワードに100を入力し[ログオン]をクリックする![ログイン画面](/img/Install/wms-login.png)

## [目次に戻る](#目次)