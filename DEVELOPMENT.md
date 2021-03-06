# ausgangssperre.io

Haupt-Repository für ausgangssperre.io.

- `index.html`: Entry-point für die App

## Local Development

To start a local server and run the app, `cd` into the repository and use any
local web server, e.g.,

```shell
$ python3 -m http.server 8000
```

Then access the app at `localhost:8000`.

### Best practices

Please keep code formatted according to our style guide :)

```shell
$ clang-format -i src/*.js
```

Keep our history linear: `git pull --rebase`.

For large code changes, please use a feature branch and ask one of the team
members for a code review before merging it into master. Use fast-forward
merges.

## Dependencies

* clang-format: `sudo apt install clang-format`
