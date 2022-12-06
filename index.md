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
    - 入荷予定一括入荷処理
    - 入荷予定一覧
  - [出荷](Ship.md)
    - 出荷グループ作成
    - 出荷帳票作成
    - 荷札データ出力
    - 問い合わせ番号登録
    - 出荷確定
    - ダッシュボード
  - [受注](ECOrder.md)
    - 受注一覧
    - 受注伝票別
    - 返品登録
  - [倉庫業務](Warehouse.md)
    - W70 在庫ロケーション一覧
    - W72 時点在庫集計
    - W74 僅少在庫リスト
    - W80 出荷実績集計
    - W82 入荷実績集計
    - W90 ロケーションマスタ
    - S80 商品在庫調整
    - S81 商品在庫調整一覧


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