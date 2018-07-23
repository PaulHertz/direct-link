---

copyright:
  years: 2018
lastupdated: "2018-05-07"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:codeblock: .codeblock}
{:pre: .pre}
{:screen: .screen}
{:tip: .tip}
{:download: .download}


# IBM Cloud Direct Link の料金 

IBM Cloud Direct Link Exchange、Connect、および Dedicated の各オファリングの料金は、以下の表に示すように、同等の地域および帯域幅で一致しています。

## IBM Cloud Exchange、Connect、および Dedicated の料金

ご使用のブラウザーで 1 Gbps 未満の速度でこの表を表示する場合、表全体を表示するには、以下のリンクを選択するか、マウスまたはトラックパッドを使用してこのページを水平にスクロールするか、このページの上部にある「GitHub で編集」をクリックしてロー・ファイルを表示してください。

[完全な表](pricing-table.html)

| 地域 | 50 mbps | 100 mbps | 200 mbps | 500 mbps | 1 Gbps | 2 Gbps | 5 Gbps | 10 Gbps |
|----|----|----|----|----|----|----|----|----|
| USA |  $100 | $150 | $300 | $650 | $1,199 | $1,999 | $3,750 | $4,999 |
| カナダ/アムステルダム |  $103 | $155 | $309 | $670 | $1,235 | $ 2,059 | $3,863 | $5,149 |
| アジア | $113 | $170 | $339 | $735 | $1,355 | $2,259 | $4,238 | $5,649 |
| 韓国 | $110 | $165 | $330 | $715 | $1,319 | $2,199 | $4,125 | $5,499 |
| オーストラリア | $120 | $180 | $360 | $780 | $1,439 | $2,399 | $4,500| $5,999 |
| インド | $120 | $180 | $360 | $780 | $1,439 | $2,399 | $4,500| $5,999 |
| パリ/フランクフルト/ミラノ |  $110 | $165 | $330 | $715 | $1,319 | $2,199 | $4,125 | $5,499 |
|ロンドン |  $107 | $161 | $321 | $696 | $1,283 | $2,139 | $4,013 | $5,349 |
| ノルウェー | $107 | $161 | $321 | $696 | $1,283 | $2,139 | $4,013 | $5,349 |
| メキシコ| $107 | $161 | $321 | $696 | $1,283 | $2,139 | $4,013 | $5,349 |
|ブラジル | $120 | $180 | $360 | $780 | $1,439 | $2,399 | $4,500| $5,999 |


## IBM Cloud Dedicated Hosting の料金

IBM Cloud Direct Link Dedicated Hosting の要求および料金は、トランザクション・ベースで処理され、ベンダーの可用性および料金に関する地域差が考慮されます。

IBM Cloud Dedicated Hosting の最小構成には、1 台のラック、5 Kw 電源、選択した速度の 2 個のポートが含まれます。追加のコロケーション・アドオンをご利用いただけます。

## ローカル・ルーティング

ローカル・ルーティングは、すべての IBM Cloud Direct Link オファリングの基本部分として組み込まれています。これには、PoP ロケーションに直接接続されているすべてのデータ・センターへのアクセスが含まれており、また無制限の発着信トラフィックが提供されます。Direct Link を注文する地域の PoP ロケーションの外部でトラフィックをルーティングする必要がある場合は、グローバル・ルーティング・オプションを追加する必要があります。そうしないと、トラフィックはローカル POP で提供されるサービスに制限されます。

## グローバル・ルーティング・アドオンの料金

グローバル・ルーティングは、すべての IBM Cloud データ・センターをグローバルに含むようにアクセスを拡張します。帯域幅は、市場に基づいて、月次で計量して課金されます。市場およびその他の考慮事項に関する詳細は、[FAQ ファイル](faqs.html#what-are-the-local-routing-and-global-routing-options)にあります。

グローバル・ルーティングを選択した場合、ローカル退出トラフィックには課金されません。ローカル PoP の外部で発着信するトラフィックのみが課金対象となります。

| 地域 | 価格 |
|---------|----------|
|USA | $2,999 |
|カナダ/アムステルダム | $2,999 |
|アジア | $2,999 |
|韓国 | $2,999 |
|オーストラリア | $2,999 |
|インド | $2,999 |
|パリ/フランクフルト/ミラノ | $2,999 |
|ロンドン | $2,999 |
|ノルウェー | $2,999 |
|メキシコ | $2,999 |
|ブラジル | $2,999 |

## 超過料金

毎月、10 Gbps 未満の回線を使用しているすべてのお客様に、10 TB の無料の退出トラフィックが割り当てられます。10 G 回線を使用しているお客様には 50 TB が割り当てられます。超過分には、次の表に基づき、一般市場レートの高い方の値が適用されます。 

|地域 | 料金 |
|--------|--------|
| 市場 1: | $0.05/GB |
| 市場 2: | $0.10/GB |
| 市場 3: | $0.15/GB |

市場について詳しくは、[FAQ ファイル](faqs.html#what-are-the-local-routing-and-global-routing-options)を参照してください。