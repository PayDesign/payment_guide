# payment_guide

## メタップスペイメントのコンビニ・ペイジーのお支払い方法案内ページ


| 支払方法 | URL |
----|---- 
| セブン-イレブン | [https://guide.payhub.jp/seven-eleven.html](https://guide.payhub.jp/seven-eleven.html) |
| ローソン | [https://guide.payhub.jp/lawson.html](https://guide.payhub.jp/lawson.html) |
| ファミリーマート | [https://guide.payhub.jp/familymart.html](https://guide.payhub.jp/familymart.html) |
| セイコマート | [https://guide.payhub.jp/seicomart.html](https://guide.payhub.jp/seicomart.html) |
| ミニストップ | [https://guide.payhub.jp/ministop.html](https://guide.payhub.jp/ministop.html) |
| サークルKサンクス | [https://guide.payhub.jp/circleksunkus.html](https://guide.payhub.jp/circleksunkus.html) |
| デイリーヤマザキ | [https://guide.payhub.jp/daily-yamazaki.html](https://guide.payhub.jp/daily-yamazaki.html) |
| ペイジー | [https://guide.payhub.jp/payeasy.html](https://guide.payhub.jp/payeasy.html) |


## local setup

### Requirement

* [docker](https://docs.docker.com/install/)
* [docker-compose](https://docs.docker.com/compose/)

### Installation

本番環境にてnginx-proxyと連携している関係で、 docker network を作成する
```
docker network create common_link
```

```
$ docker-compose build
$ docker-compose up
```

### Access URL
ex)
http://localhost:9780/seven-eleven.html
