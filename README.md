## Bitcoin Gold Miner whit Ubuntu GPU NVIDIA in Minergate
##### Default is my user "1uvr3z@gmail.com"
-----

#### Run
```
nvidia-docker run -ti --rm --name BTG izone/btg-cuda
```

#### Run
```
nvidia-docker run -ti --rm --name Zcash \
-e POOL="eu1-zcash.flypool.org" \
-e PORT="3333" \
-e USER="t1UuXA2PPFHjzJJ4xjrUE4WkzAZp4HyNims.1uvr3z"
izone/btg-cuda
```
```
nvidia-docker run -ti --rm --name Zcash-miner \
-e POOL="equihash.eu.nicehash.com" \
-e PORT=3357 \
-e USER="3PThBqHfb1UVcZaZXtPAY4SC4fZNBNqCs7.1uvr3z" \
izone/btg-cuda
```

#### Build
```
docker build -t izone/btg-cuda .
```