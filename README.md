# ScaffoldでのTodoを作成するサンプル

## rails6.0.3でアプリを作成する

```linux
rails _6.0.3_ new todo --skip-action-mailer --skip-action-mailbox --skip-action-text --skip-action-storage --skip-action-cable
```

## scaffoldで色々と作成する

```linux
rails generate scaffold task content:text
```

## dbを作成する

```linux
rails db:create
```

## dbのマイグレーションを実行する

```linux
rails db:migrate
```
