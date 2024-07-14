# AnomalyDetectionTutorial
「Pythonではじめる異常検知入門」でのサンプルコード

## WSL上でcondaコマンド利用を準備
Anacondaのパスを通し、condaコマンドが利用可能か確認する。  
```shell
wget https://repo.anaconda.com/archive/Anaconda3-2024.06-1-Linux-x86_64.sh
bash Anaconda3-2024.06-1-Linux-x86_64.sh

export PATH=/root/anaconda3/bin:$PATH
```

## 仮想環境作成

以下のコマンドで仮想環境を作成する。  
```shell
conda create -n {環境名} python=3.9.13
```
