# Exploratory-Data-Analysis
* Exploratory Data Analysis(探索的データ解析)のプログラム

## リポジトリ構成
```
.
├── README.md                 READMEファイル
├── .dockerignore        
├── Dockerfile                Dockerファイル
├── docker-compose.yml
├── notebook                  jupyter notebook
└── data                      dataファイル
```

## 環境構築

* Dockderfileがあるホスト側のフォルダへ移動（例：Desktop/Exploratory-Data-Analysis）
```
cd Desktop/Exploratory-Data-Analysis
```

* Dockerによる環境構築（フォルダをマウント：Desktop/Exploratory-Data-Analysis）
```
docker-compose up --build
```

* ブラウザーを立ち上げてlocalhost:8888へアクセス
* ローカルフォルダがマウントされている

## jupyter notebook説明
* Sweetviz.ipynb : Sweetvizを活用したEDAのnotebook
* Pandas-profiling.ipynb : Pandas-profilingを活用したEDAのnotebook
* autoviz.ipynb : autovizを活用したEDAのnotebook
* dtale : dtaleを活用したEDAのnotebook


## 動作環境
マシンスペック（Mac)
- MacBook Air (Retina, 13-inch, 2018)
- 1.6 GHz デュアルコアIntel Core i5
- 8 GB 2133 MHz LPDDR3
