# docker-wiremock
wiremock docker-compose

mappings、filesの配下にworemockのモックファイルを作成し
`docker-compose up -d` で起動すると　
`localhost:8787/__admin/` に作成したマッピングの一覧が表示されます。

sampleとして２つのAPI Mockを作成しているので以下でアクセスするとjsonが返ります。

`localhost:8787/sample`
`localhost:8787/test`

## mockの作成

filesの配下にレスポンスを記述。
mappings配下にルールを記述し、再起動すればOKです。
