
```
rackup
configuration /home/negabaro/docker/sinatra-study/config.ru not found
```


error

```
rackup
/usr/local/rbenv/versions/2.4.1/lib/ruby/2.4.0/rubygems/specification.rb:2291:in `raise_if_conflicts': Unable to activate sinatra-1.4.8, because rack-2.0.5 conflicts with rack (~> 1.5) (Gem::ConflictError)
```

```
gem list |grep sinatra
sinatra 1.4.8
```

```
gem update sinatra
```

```
gem list |grep sinatra
sinatra (2.0.4, 1.4.8)
```


# reference

http://aligach.net/diary/20110307.html