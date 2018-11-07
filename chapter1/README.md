# default

```
ruby app.rb 
== Sinatra (v1.4.8) has taken the stage on 4567 for development with backup from Puma
Puma starting in single mode...
* Version 3.12.0 (ruby 2.4.1-p111), codename: Llamas in Pajamas
* Min threads: 0, max threads: 16
* Environment: development
* Listening on tcp://localhost:4567
Use Ctrl-C to stop
```

# -o

```
ruby app.rb  -o 0.0.0.0
== Sinatra (v1.4.8) has taken the stage on 4567 for development with backup from Puma
Puma starting in single mode...
* Version 3.12.0 (ruby 2.4.1-p111), codename: Llamas in Pajamas
* Min threads: 0, max threads: 16
* Environment: development
* Listening on tcp://0.0.0.0:4567
Use Ctrl-C to stop
```

# -p

```
ruby app.rb  -o 0.0.0.0 -p 3004
== Sinatra (v1.4.8) has taken the stage on 3004 for development with backup from Puma
Puma starting in single mode...
* Version 3.12.0 (ruby 2.4.1-p111), codename: Llamas in Pajamas
* Min threads: 0, max threads: 16
* Environment: development
* Listening on tcp://0.0.0.0:3004
Use Ctrl-C to stop
```

# 参照

https://suruseas.github.io/ruby/2016/11/30/sinatra-rackup-outside.html
