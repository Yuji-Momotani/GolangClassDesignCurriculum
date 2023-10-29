# GolangClassDesignCurriculum

クラス設計カリキュラム用のリポジトリ（Golang + clean-architecture,DDD）

## PlantUML のローカル起動

- VSCode の拡張子をインストール
  [PlantUML](https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml)

- Docker 起動

```sh
docker run -d -p 8090:8080 plantuml/plantuml-server:jetty
```

- Extention の設定
  「Configure Extension Settings」を選択し、以下の項目を設定

  - Plantuml: Render → PlantUMLServer
  - Plantuml: Server → http://localhost:8090

- ファイル作成後、プレビューで確認
  macOS のショートカット、「Option + D」でプレビューが確認できる。

参考：https://dev.classmethod.jp/articles/plantuml-server-on-docker/
