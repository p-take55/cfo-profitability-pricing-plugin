---
name: cfo-profitability
description: 商品・顧客・案件ごとの利益、原価、工数、損益分岐点を比較するときに使う。
metadata:
  aachat.headline.ja: "商品・顧客・案件ごとの利益と損益分岐を出す"
  aachat.headline.en: "Profit and break-even by product, customer and project"
  aachat.description.ja: "限界利益・固定費・本人の工数を分けて比べ、損益分岐の数量と、実際に提供できる量を照らし合わせる。"
  aachat.description.en: "Compares contribution margin, fixed costs and your own hours separately, and checks the break-even volume against what you can actually deliver."
  aachat.discovery.listed: "true"
---

# 商品・顧客・案件別の採算分析

対象期間と通貨・税区分を揃え、売上、数量、値引き・返金、変動費、固定費、本人の工数を確認する。計上済みの給与・外注費と仮の時間コストを二重に差し引かない。
限界利益＝売上－変動費。固定費控除前を最終利益と呼ばない。配賦する場合は配賦前後と基準を示し、未配賦・未分類を全体へ照合する。
単一商品の損益分岐数量＝固定費÷（単価－単位変動費）。整数単位なら切り上げる。単位限界利益がゼロ以下なら販売量を増やして回収できるとしない。複数商品には販売構成を無視して同じ式を当てない。

本人の工数は独立した欄に置く。指定された時間単価がある場合だけ参考時間コストを計算する。空いた時間を自動的に売上や現金の増加へ換算しない。
必要販売量と提供可能量を照合する。顧客別では初回導入と継続対応、案件別では未完了・追加対応を区別し、期間の違いで順位を誤らない。
成果は採算比較、工数、共通費の扱い、改善候補、判断を変える欠落。販売構成や将来工数を仮定した数値には仮定を付ける。
計算の根拠は [references/evidence.md](references/evidence.md)。
