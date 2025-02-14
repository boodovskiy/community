# サブクエリネットワーク - サマリー

> SubQuery Networkはどのように機能しますか? [ELI5](https://www.dictionary.com/e/slang/eli5/#:~:text=ELI5%20stands%20for%20the%20phrase,naive%20understanding%20of%20the%20issue.)

今日はSubQuery Networkがどのように高レベルで動作するかについてお話します。

## 参加者


![](https://miro.medium.com/max/1400/1*9993cakplwupZC5tbUv3vA.png)

SubQuery Networkの参加者

SubQuery Networkには、3つのタイプの参加者がいます。

-   **コンシューマー**: SubQuery Networkに特定のデータを要求し、SQTの広告された金額を支払います。
-   **インデックス**: インデックスは、独自のインフラストラクチャでSubQuery Projectsをホストします。 ノードとクエリサービスの両方を実行して、データのインデックスとGraphQLリクエストに答えます。
-   **デリゲーター**:デリゲーターは、お気に入りのインデクサーをサポートして報酬を獲得することでネットワークに参加します。

## インデックス、コンシューマー、クエリ

インデクサーから始めましょう。インデクサーは裏で多くの努力をしています。 ハードウェアの管理、インフラストラクチャの実行、リソースの監視、インデックスする適切なSubQueryプロジェクトの選択。

これには時間とお金がかかりますが、これを手に入れると、消費者が来てリクエストを行うことがあります。 コンシューマー: SubQuery Networkに特定のデータを要求し、SQTの広告された金額を支払います。

![](https://miro.medium.com/max/1400/1*dKLkzSc2uXYaPW_IXUxstQ.png)

コンシューマー: SubQuery Networkに特定のデータを要求し、SQTの広告された金額を支払います。

## コブダグラス生産機能

このお支払いはプロジェクトの収益プールに入り、ステーキング時代(28日間)の終わりにこのプロジェクトの収益プールを分割します。 コブダグラス生産機能と呼ばれるものによってインデクサー全体に唾を吐く。

![](https://miro.medium.com/max/1400/1*E-W7o7cWoclxHb8rXAMdpA.png)

コブダグラス生産機能と呼ばれるものによってインデクサー全体に唾を吐く。

このアプローチは、簡単に教えると、収益が競合するインデクサに割り当てられ、リクエストの回答と投資額の両方の割合で割り当てられることを意味します。

![](https://miro.medium.com/max/1400/1*VhDu2BGDxd3ob7z9XkoOXA.png)

収益は競合するインデクサに割り当てられ、リクエストの回答と投資額の両方の割合としています。

私たちの見解ではこの方程式の素晴らしい点は合理的なインデクサーが 最適な収入を得るために彼らが行う仕事と比べて 高いレベルの SQT を維持しなければならないことです。 その結果として、 ゲーム内のステークやスキンを自己管理し維持するためにインデクサがインセンティブを与えられているため、任意のステーキング要件を実施する必要はありません。

## デリゲート

インデックス作成者は可能な限り多くの作業を行い、報酬を最大限に活用するようにインセンティブを与えられます。 ここでデリゲートがやってきます。

代理人はスペアSQTをインデックスに委任することができ、それぞれのインデクサは _クエリ手数料収益率_を公開することができます。 それらの代表者は、インデクサーが報酬を受け取った問い合わせ料金の一部で報酬を受け取ることになります。

![](https://miro.medium.com/max/1400/1*YoN7PV7h3a2nAFN-ODqILg.png)

代理人はスペアSQTをインデックスに委任することができ、それぞれのインデクサは クエリ手数料収益率を公開することができます。 それらの代表者は、インデクサーが報酬を受け取った問い合わせ料金の一部で報酬を受け取ることになります。

インデックス作成者が宣伝する _クエリ手数料収入率_ は、28日間の投資期間ごとにロックされています そしてその減少は28日間の投資の時代に宣伝されなければなりません。

同様に、代表者は任意の時点で委任金額を削除することができますが、投資時代全体に委任した場合にのみ報酬を受け取ることができます。

![](https://miro.medium.com/max/1400/0*we0k4A07pbj86COZ)

委任すると報酬を受け取ることができます。

## 購買発注

プロジェクトのインデックス作成には時間とお金がかかります。チェーンには多くのデータがあります。 インデックス作成者がまったく新しいSubQuery Projectをサポートするようにするために。 新しいSubQuery ProjectsのIndexersへの確実な収入を示すための市場メカニズムを実装する予定です。

私たちはそれらを購入注文と呼んでおり、消費者は設定された価格とリクエスト数のためにチェーン上の契約を宣伝することができます。 インデクサはこれを表示し、コントラクトを埋めることを選択できます。

![](https://miro.medium.com/max/1400/1*IPtaZlt24E7h9bKNZWdSCw.png)

消費者は、設定された価格とリクエスト数のためにチェーン上で注文を宣伝することができます。

購入注文は、既存のSubQuery Projectsに配置して、競争を改善し、価格を下げるために追加のIndexersを引き付けることもできます。