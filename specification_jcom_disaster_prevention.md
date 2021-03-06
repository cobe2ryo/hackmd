# J：COM次期防災BOXの機能要求まとめ
## Type A

| 要求機能 | 備考 |
| -------- | -------- |
| 放送波受信（Lと防災行政無線）のみ音声のみ  | 緊急地震速報は含まない。（ソフトウェア対応）<br>Lはバックエンドが音声合成して配信。<br>あるいは、液晶がつくなら文字表示でも可！？<br>防災行政無線は現在70の自治体の防災行政無線卓から直収している。<br>今後、アルカディアとの協業で拡大を模索する。 |
| ラジオチューナーはあり | -------- |
| 液晶なし。インジケーターくらいはいるかしら | 防災端末に必須である電源状態や受信状態を<br>コミュニケーションするためのLEDインジケーターを<br>搭載するくらいなら液晶のほうが単価が下がる？<br>その場合液晶ありで積算。 |
| 通信（SIM）なし | -------- |
| BTあり（BLEチップに変更）送受信対応必要 | スマホと連携し、スマホから端末側に設定情報（市町村コード・エリアコード・グループID・国籍性別！？）を送り込む。ソフトウェアをどうするかは要検討。液晶があればスマホ側の設定ソフトウェアは必要なくなる？ |
| HDMIなし | RGBから外付けHDMI変換なら可（Type Aは蓋する） |
| ロッドアンテあり | -------- |
| RF端子（F接栓） | 初期アイディアではロッドアンテナによる地上波受信のみを<br>想定していたが、屋内での確実な受信のため、<br>コミュチャン帯域の利用を提案（当然マスター設備への投資が必要／エリア外はロッドアンテナのみ）。<br>現在は76MHzを活用?|
| シングルチューナー | 地デジチューナー／FMチューナー|
| ワンセグと12セグの両対応 | 12セグ待受対応に変更|
| OTAあり | 利用帯域は要検討。ブート先2系統化 |
| LPWAあり | 当初アンサーバック利用としてのLPWAはType Bでの搭載を予定していたが、配布コスト（キッティング・宅内セットアップ）低減のため、コンフィグ放送とアンサーバックの組み合わせが有効であると提案し、Type Aにも搭載するべきと判断|
| 防水 | なし|
| SDK対応（開発環境） |ソフトウェアの外部化|

## Type B

| 要求機能 | 備考 |
| -------- | -------- |
| 液晶 | Type Aで搭載するなら検討する必要なし|
| 緊急地震速報 | Type AでRF端子がつくことになると、サービスとしての問題？現状は76MHzを活用。|
| スマホ連動 | 防災BOXで受信したコンテンツを、スマートフォンに伝搬することで<br>通信断絶時にもスマホでコンテンツを受信し、最適な体現系を実現できる。<br>Beacon CastまたはDTNの活用？|

## 見積もり条件

1. 発注ロット
* 5,000
* 10,000
* 50,000
* 100,000
* 500,000
* 1,000,000
* 5,000,000

1. 見積もりパターン
* 開発費別
* 開発費込

1. 最短納品期間
* それぞれの発注ロッドにおいて、最低納品期間（ソフトウェア別）

## 備考
* RFIで見積もり依頼をする必要があるよ→RFPを複数社に
* 商社を挟んでリスク管理（テクニカルサポート）する？調達部マター
* リコール時の対応に体力いるよね。AIWA大丈夫？
* 無料配布、販売、自治体配布（自治体配布はJ:COM）
* AIWAブランドを表示するかにはこだわらない
* 金型は50,000くらいでだめになるので、大量発注の場合、金型製造は必須。そうなると大量発注の場合、金型から起こし直しも視野に




