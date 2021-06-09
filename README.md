# resh
A shell repo mainly for bash
goto /l for stuff 
to import a lib 

note the REPO env var for this repo wought be set to https://raw.githubusercontent.com/lnee94/resh/main/l
with export 

```REPO="https://raw.githubusercontent.com/lnee94/resh/main/l"```    

```eval "$(rl -s $REPO/insert-here)"```

or import resher with
```eval "$(curl -s $REPO/resher)"```
```resher insert-here```

you download the text and add that to your shell script
