# README

## Database

- Execute as migrações

```sh
rails db:migrate
```

## Run

- Para executar este projeto, configure o arquivo credentials.yml.enc, para isto execute:

```sh
EDITOR="code --wait" bin/rails credentials:edit 
```

- Depois adicione:

```yaml
authenticate:
  name: admin
  password: admin
```

- Por fim, execute:

```sh
rails s
```
