# 0418 イベント用 サンプルアプリ

## Ruby version
2.2.0

## Rails version
4.2.0

## コマンド
クローン後に

```
bundle install
bundle exec rake db:migrate
bundle exec rake db:seed
bundle exec rails s -p 3000
```

の後に、

`http://localhost:3000/products`

にアクセス。


## Productモデルの構造
```
id: intger
name: string
price: integer
```