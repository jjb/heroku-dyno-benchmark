# heroku-dyno-benchmark

`heroku buildpacks:add --index 1 heroku-community/apt`

`heroku run bash --size=standard-1x` or `2x`

```sh
sysbench cpu --cpu-max-prime=10000 --threads=1 run
sysbench cpu --cpu-max-prime=10000 --threads=2 run
sysbench cpu --cpu-max-prime=10000 --threads=8 run
```

results:

https://docs.google.com/spreadsheets/d/1x5ev9WZ8rQw_pF0Ji_-B_rYqzEnDA_KGJCVtVJEUCAM/edit?usp=sharing

