# 出荷
- 出荷グループ作成~出荷確定まで
  - [出荷グループ作成](#n10-出荷グループ作成)
  - [出荷帳票作成](#n15-出荷帳票作成)
  - [荷札データ出力](#w13-荷札データ出力)
  - [問い合わせ番号登録](#w40-各種データ取り込み)
  - [出荷確定](#w50-出荷確定)
  - [ダッシュボード]()

## N10 出荷グループ作成
1. サイドメニューの出荷(N)から出荷グループ作成(N10)を開きます。![N10メニュー](/img/Ship/N10_Menu.png)
2. 出荷場所を選択することで出荷グループを作成できる一覧が表示されます。![N10デフォルト](/img/Ship/N10_Default.png)
3. 右枠の[オーダー明細]のタブを選択するとグループ内のオーダー別で明細が表示されます。![N10オーダー明細](/img/Ship/N10_OrderDtl.png)
4.  右枠の[パターン明細]のタブを選択するとグループ内のSKUの組み合わせで表された明細が表示されます。![N10パターン明細](/img/Ship/N10_PatternDtl.png)
5.  グループを作成する方法は3種類あります。
    1.  左枠の出荷グループ作成の行で作成
        1. 左枠の[出荷先]の画面からチェックボックスを選択します。
        2. [グループ新規作成]の欄に分かりやすい出荷グループ名を入力します。
        3. [待ち⇔準備]ボタンをクリックします。![左枠から出荷グループ作成](/img/Ship/N10_ShippingGroupMake_leftUI.png)
    2.  オーダー明細から作成
        1. 特定のオーダーNoで出荷グループを作成したい場合、利用します。
        2. 右枠の[オーダー明細]の画面から該当オーダーのチェックボックスを選択します。
        3. [グループ新規作成]の欄に分かりやすい出荷グループ名を入力します。
        4. [待ち⇔準備]ボタンをクリックします。![オーダー明細から出荷グループ作成](/img/Ship/N10_ShippingGroupMake_OrderDtl.png)
    3. パターン明細から作成
       1. 特定のパターン明細で出荷グループを作成したい場合、利用します。
       2. 右枠の[パターン明細]の画面から指定したいパターン件数を選択します。
       3. [グループ新規作成]の欄に分かりやすい出荷グループ名を入力します。
       4.  [更新]をクリックします。![パターン明細から出荷グループ作成](/img/Ship/N10_ShippingGroupMake_PatternDtl.png)

## N15 出荷帳票作成
1. サイドメニューの出荷(N)から出荷帳票作成(N15)を開きます。![N15メニュー](/img/Ship/N15_Menu.png)
2. 作成した出荷グループの帳票を作成する一覧が表示されます。![N15](/img/Ship/N15_Default.png)
3. 作成する帳票を右枠からチェックボックスで選択し、[帳票作成]ボタンをクリックすると印刷対象 (左枠)に移動します。![N15右枠から帳票作成対象へ](/img/Ship/N15_DelivSip_to_leftUI.png)
4. 印刷対象から印刷したい行を選択します。
5. ピッキングリストと納品書を印刷するプリンターを選択します。
6. 出荷指示書単票とパターンリストを印刷する場合はチェックボックスを付けます。
7. [印刷]ボタンをクリックすると指定したプリンターから帳票が出力されます。![N15印刷](/img/Ship/N15_DelivSip_Print.png)
   1. 出荷指示書例![出荷指示書](/img/Ship/Sample/PickingList.png)
   2. トータルピッキングリスト例![ピッキングリスト](/img/Ship/Sample/TotalPickingList.png)
   3. 出荷指示書単票例
      1. ![出荷指示書単票](/img/Ship/Sample/SimplePickingList.png)
   4. パターンリスト例
      1. ![パターンリスト](/img/Ship/Sample/PatternList.png)
   5. 納品書例
      1. ![納品書](/img/Ship/Sample/DelivSlip.png)

## W13 荷札データ出力
1. サイドメニューの倉庫(W)から荷札データ出力(W13)を開きます。![W13メニュー](/img/Ship/W13_Menu.png)
2. [新規出力]のタブで荷札データを新規で出力する出荷グループが表示されます。[再出力]のタブで再度出力できる出荷グループが表示されます。![W13初期画面](/img/Ship/W13_Default.png)
3. 荷札データを出力したい行のチェックボックスを付けます。
4. [出力]ボタンをクリックし、保存したいPC内の場所を選択します。![W13出力画面](/img/Ship/W13_shipDataExport.png)

## W40 各種データ取り込み
1. サイドメニューの倉庫(W)から各種データ取り込み(W40)を開きます。![W40メニュー](/img/Ship/W40_Menu.png)
2. 各配送会社からダウンロードした出荷データを取り込むことで問い合わせ番号を一括更新できます。赤枠内のヤマト運輸、佐川急便、日本郵便、DHLが対応可能です。![W40](/img/Ship/W40_DataImport_TransInvNo.png)
3. [..]ボタンをクリックし、ダウンロードした出荷データCSVを選択します。
4. [事前チェック]ボタンをクリックする事で事前にエラーが出た際の内容を確認できます。
5. [登録]ボタンをクリックするとエラー以外の行が一括更新されます。![W40](/img/Ship/W40_BulkUpdate.png)

## W50 出荷確定
1. サイドメニューの倉庫(W)から出荷確定(W50)を開きます。![W50メニュー](/img/Ship/W50_Menu.png)
2. 出荷確定ができる出荷一覧が表示されます。
   1. [問番有り]には問番が入力されている出荷データが表示されます。[問番無し]には問番無しで確定できる配送会社の出荷データが表示されます。![W50初期画面](/img/Ship/W50_Default.png)
3. 出荷確定したいデータのチェックボックスを付けます。[全選択]ボタンをクリックする事で全行選択する事も可能です。
4. [確定]ボタンをクリックする事で確定できます。![W50出荷確定](/img/Ship/W50_ShipFix.png)

## Z10 ダッシュボード
1. サイドメニューからダッシュボード(Z10)を開きます。![Z10メニュー](/img/Ship/Z10_Menu.png)
2. 受注・出荷・入荷の進捗が確認できます。[出荷作業中]の出荷が残っていないかのチェックができます。![Z10初期画面](/img//Ship/Z10_Default.png)