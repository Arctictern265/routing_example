# ルート検索プラグイン例

QGIS APIを使ったルート検索プラグインの実装例です。

## インストール

QGISのプラグインディレクトリに展開後、メニューの【Plugins】ー【Manage and Install Plugins】を選択してプラグインマネージャを開き、左側のリストパネルで「Installed」を選択すると本プラグインが右側のリストに表示されます。ここで本プラグインにチェックを入れて有効にしてください。

![plugin manager](https://github.com/Arctictern265/routing_example/blob/files/plugin_manager.png)


## サンプルファイル

以下のURLよりダウンロードをお願いいたします。
https://github.com/Arctictern265/routing_example/blob/files/map.gpkg

サンプルファイルにはいくつかのレイヤが含まれています。ルート検索の対象とするレイヤは"roads"です。

## 使用方法

プラグインを起動すると以下のダイアログが表示されます。ここで、ルート検索の対象とするレイヤを選択します。

![select layer dlg](https://github.com/Arctictern265/routing_example/blob/files/select_layer_dlg.png)

選択後、［OK］ボタンを押すとカーソルが十字に変化します。ルート検索を実行するには、まずキャンバスから始点をマウスの左ボタンでクリックします。クリックすると下図のようなマーカーが表示されます。

![start point flag](https://github.com/Arctictern265/routing_example/blob/files/start_point_flag.png)

続いて終点となる点をマウスの左ボタンでクリックします。クリックと同時に検索が実行され、下図のようにルート検索結果が緑色で表示されます。

![routing result](https://github.com/Arctictern265/routing_example/blob/files/routing_result.png)

検索結果を消去、またはルート検索をキャンセルする場合はキャンバス上でマウスの右ボタンを押します。


