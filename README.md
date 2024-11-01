# marping

setting docker
```
docker pull marpteam/marp-cli
```

compile to html
```
docker run --rm -v $PWD:/home/marp/app/ -e LANG=$LANG marpteam/marp-cli slide-deck.md
```

serve http-server
```
npx http-server
```
