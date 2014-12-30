How to use
----

Install the [HTTPSEverywhere](https://www.eff.org/https-everywhere) browser
extension. Clone this repo to its user rules directory. E.g. for Firefox on
Linux:

```sh
profile="Your profile directory name"
cd ~/.mozilla/firefox/${profile}/HTTPSEverywhereUserRules
git init
git remote add lilydjwg git@github.com:lilydjwg/HTTPSEverywhereUserRules.git
git pull -u lilydjwg master
```

Restart Firefox and it should work.
