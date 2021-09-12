# ERRATA.md

## OpenDAX install

1. Use this:

```
app@...:~$ curl -sSL https://rvm.io/mpapis.asc | gpg --import -
app@...:~$ curl -sSL https://rvm.io/pkuczynski.asc | gpg --import -
```

instead of:

```
gpg --keyserver hkp://keys.gnupg.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3 7D2BAF1CF37B13E2069D6956105BD0E739499BDB
```

due to https://stackoverflow.com/questions/66217436/gpg-keyserver-receive-failed-no-name error.
