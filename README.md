# NetworkConstruction

北九州高専／5I／ネットワーク構成論の講義で使用したDocker環境です。

## Requirement

- docker-compose
 
## Installation
 
1. clone repository
```sh
git clone git@github.com:Futaba-Kosuke/NetworkConstruction.git
cd NetworkConstruction
```

2. build
```sh
docker-compose buid

# 個別ビルド
docker-compose build {$container_name}
```
 
## Usage
 
```bash
# 全て起動
docker-compose up
# 個別に起動
docker-compose up -d {$container_name}

# コンテナに入る
docker-compose exec {$container_name} bash

# コンテナ起動〜入るまで
dokcer-compsoe run {$container_name} bash
```

## Used
- docker-compose
- ubuntu 20.04
