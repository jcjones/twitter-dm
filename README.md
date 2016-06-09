# Usage

Setup an OAuth1 http.Client with the consumer key and secret and oauth token and secret.

```
export TWITTER_CONSUMER_KEY=xxx
export TWITTER_CONSUMER_SECRET=xxx
export TWITTER_ACCESS_TOKEN=xxx
export TWITTER_ACCESS_SECRET=xxx
```

Then install:
```
go get github.com/jcjones/twitter-dm
```

Use with:
```
twitter-dm -recipient MyTwitterHandle -message "This message was sent!!"
```


