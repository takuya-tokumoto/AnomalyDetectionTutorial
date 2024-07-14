# AnomalyDetectionTutorial
「Pythonではじめる異常検知入門」でのサンプルコード

## 環境準備
今回はWSL(Windows Subsystem for Linux)上にて環境を準備

### (初回のみ)condaコマンドの有効化
WSL上でcondaコマンドを利用できるよう準備
Anacondaのパスを通し、condaコマンドが利用可能か確認する。  

```shell
wget https://repo.anaconda.com/archive/Anaconda3-2024.06-1-Linux-x86_64.sh
bash Anaconda3-2024.06-1-Linux-x86_64.sh

export PATH=/root/anaconda3/bin:$PATH
```

### 環境作成

以下のコマンドで仮想環境を作成する。  
```shell
conda create -n {環境名} python=3.9.13
conda activate {環境名}

pip install -r requirements.txt --user
```
