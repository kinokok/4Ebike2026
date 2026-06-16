## E-Bike Project 2026

舞鶴市 電動自転車のための観光ナビWebアプリケーション<br>

#### 構成
`E-Bike-main/`<br>
├── <br>
└──<br>
<br>

`ViisProject/`<br>
├── `main.html` 地図表示<br>
├── `maizuru_spots.js` スポットデータ<br>
├── `maizuru_spots_rejected.js` 削除済みスポットデータ<br>
├── `routes.js` ルートデータ<br>
├── `routemade.html` ルート追加用<br>
└── `spotmade.html` スポット追加用<br>

<br>

#### ToDo

- スポット・おすすめルートの追加
- ルート自作機能の実装
- 予想走行距離・到着時間の表示
- 多言語化
- 現在地点の取得・表示
- ピンに画像を追加


#### 貢献
`あ`<br>
- スポット検索・ルート案内を網羅したサイトのフロントエンド作成(main.html)
├── 地図表示にleafletの選定、地図表示範囲の限定、ズームイン・アウトの制限
├── Overpass API、ホットペッパーAPIを用いて観光スポットの一括抽出(maizuru_spots.js)
├── jsonをリスト形式に変換し、一元管理(jsonTOjs)
├── 地図上に観光スポットマーカーの自動配置
├── マーカークリックでポップアップの表示
├── 表示範囲内のスポット一括検索
├── 単語でのスポット検索機能の実装
├── カテゴリー別でのスポット検索機能の実装
├── ルートのgoogle map遷移機能実装
├── html外観の調整・プロトタイプの実装
-  ルート作成サイトの実装(routemade.html)
-  タスク・ディレクトリ構成の明瞭化(readme)
-  githubでリポジトリ作成・プロジェクト全体の管理



スポット情報はOverpass API、ホットペッパーAPIで取得
