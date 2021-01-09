# plantuml_work

## 環境構築
前提
- dockerが使える
- docker-composeが使える

やること
- VSCodeの拡張機能`PlantUML`をインストール
- Extension settingsから以下を設定
  - Plantuml:Render -> PlantUML Server
  - Plantuml:Server -> http://localhost:8080

## 使い方
PlantUMLを書く時に、以下のコマンドでローカルにPlantUML Serverを起動する。
```
$ docker-compose up -d
```

あとは、puファイルを作成し、vscodeのplantuml拡張の機能でpreviewしたりexportしたりできる。