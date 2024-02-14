# saga study

Saga のお勉強用リポジトリ

## Saga とは

- 分散アプリケーションの一貫性を確立するためのアーキテクチャパターン
- 複数のマイクロサービス間のトランザクションを調整して、データの一貫性を維持する

以下のような場合に、Saga パターンを検討する

- アプリケーションの密結合を避けた上で、複数のマイクロサービス間でデータの一貫性を維持する必要がある
- トランザクションの存続期間が長く、一つのマイクロサービスが長時間実行されても、他のマイクロサービスがブロックされることを避けたい
- シーケンス内のそれぞれのトランザクションが一つでも失敗した場合に、ロールバックを行う必要がある

参照：[Patterns for enabling data persistence - Saga pattern](https://docs.aws.amazon.com/prescriptive-guidance/latest/modernization-data-persistence/saga-pattern.html)
