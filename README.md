## Go lien App HEROKU:
# https://test1appigwen.herokuapp.com/

## Voir mon code:
```
$ git clone https://github.com/Gwekkeo/app-with-back-end.git
```
```
$ cd app-with-back-end
```

## Etapes:
* Installation des gems (sans la production)
* Lancement des migrations

```
$ bundle install --without production
```
```
$ rails db:migrate
```
```
$ rails server
```

```
$ localhost:3000
```

### Si probleme avec rails server
```
$ rails server -p 4567
```
```
$ localhost:4567
```

### Version ruby
ruby '2.5.1'

Fait par CASSAND Gwendoline
