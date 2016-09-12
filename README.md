# ClojureBridge London Website

This is our website to document our events even when they disappear from the main clojurebridge.org website.

https://clojurebridgelondon.github.io

## Coaches Training slides

The source document lives under `docs/coaches_training.deck.md`. To recreate the HTML use

```
gem install deckrb
deck -b docs/coaches_training.deck.md
```

## Contribute

How to get started:
```
git clone git@github.com:clojurebridgelondon/clojurebridgelondon.github.io.git
cd clojurebridge-berlin.github.io
git pull
jekyll serve
```
Maybe you have to install Jekyll if the last command doesn't work.
```
gem install jekyll
```
In your browser go to:
http://localhost:4000/
