# Exploratory-Data-Analysis

- Exploratory Data Analysis(探索的データ解析)のプログラム

## リポジトリ構成

```
.
├── Dockerfile
├── README.md
├── data
│   └── Boston.csv
├── docker
│   ├── autoviz
│   │   ├── Dockerfile
│   │   └── requirements.txt
│   ├── dtale
│   │   ├── Dockerfile
│   │   └── requirements.txt
│   ├── pandas-profiling
│   │   ├── Dockerfile
│   │   └── requirements.txt
│   └── sweetviz
│       ├── Dockerfile
│       └── requirements.txt
├── docker-compose-autoviz.yml
├── docker-compose-dtale.yml
├── docker-compose-pandas-profiling.yml
├── docker-compose-sweetviz.yml
├── docker-compose.yml
├── docs
├── models
├── notebooks
│   ├── autoviz
│   │   └── autoviz.ipynb
│   ├── dtale
│   │   └── dtale.ipynb
│   ├── pandas-profiling
│   │   ├── Pandas-profiling.ipynb
│   │   └── Pandas-profiling_report.html
│   └── sweetviz
│       ├── Sweetviz.ipynb
│       ├── sweetviz_report_1col.html
│       └── sweetviz_report_2col.html
├── pyproject.toml
├── setup.cfg
├── src
│   └── __init__.py
├── tests
│   └── __init__.py
└── work
```

## 環境構築

- Dockderfileがあるホスト側のフォルダへ移動（例：Desktop/Exploratory-Data-Analysis）

```
cd Desktop/Exploratory-Data-Analysis
```

- Dockerによる環境構築（フォルダをマウント：Desktop/Exploratory-Data-Analysis）

```
docker-compose -f docker-compose-{*構築対象}.yml up --build
```

- ブラウザーを立ち上げてlocalhost:8888へアクセス
- ローカルフォルダがマウントされている

## Display notebooks

- [View Jupyter notebooks in nbviewer](https://nbviewer.jupyter.org/github/ykato27/Exploratory-Data-Analysis/tree/main/notebooks/)

## 動作環境
マシンスペック（Mac)
- MacBook Air (Retina, 13-inch, 2018)
- 1.6 GHz デュアルコアIntel Core i5
- 8 GB 2133 MHz LPDDR3
