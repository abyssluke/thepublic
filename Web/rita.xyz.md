# rita.xyz
ブログなどで使われている一部の画像データやspamの晒しあげ会場として使われている。
Amazon S3 + Amazon CloudFront + Amazon Route53を使っており、AWSのインフラで生きてるやつ。

さらにはSSL通信もできるらしい(通常は未使用)。

なお、rita.xyzはGitでバージョン管理していたりする。あくまでローカルでの管理なのでリモートレポジトリは設定していないが。

HTTPヘッダーを見るとわかるがs3cmdを使ってアップロードしている。

## おまけ

### ぬるぽ
http://rita.xyz/nullpo.html

### DNSでお遊び
以下のサブドメインにはどうでもいいTXTレコードのみが設定されている。

* nullpo
* nurupo
* warning

