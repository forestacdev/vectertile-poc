# 岐阜県美濃市 地質図ベクトルタイル

このリポジトリは、「産総研 地質調査総合センター」が提供している 5 万分の 1 地質図幅の岐阜県美濃市のデータをベクトルタイルに変換したものです。

## タイル URL

`https://raw.githubusercontent.com/forestacdev/vector-tiles-gifu-mino-geology/main/tiles/{z}/{x}/{y}.pbf`

最大ズームレベル: 14

最小ズームレベル: 0

## データソース

「産総研 地質調査総合センター」

https://www.gsj.jp/Map/JP/geology4-10.html#10082

## データ構造

| source-layer | 詳細                       | データ種別 |
| ------------ | -------------------------- | ---------- |
| geo_A        | 地質分布の面情報           | ポリゴン   |
| geo_L        | 地質境界等の線情報         | ライン     |
| gfd          | 背斜向斜軸等               | ライン     |
| pnt          | 点で表される位置情報       | ポイント   |
| sec          | 断面線情報（断面図は除く） | ライン     |
| strdip       | 走向傾斜                   | ポイント   |

## 属性対応表

- [LEGEND_LINE](doc/LEGEND_LINE.md)
- [LEGEND_POLY](doc/LEGEND_POLY.md)
- [PNT](doc/PNT.md)
- [RGB](doc/RGB.md)
- [STRDIP](doc/STRDIP.md)
