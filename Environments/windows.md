# PyCourse 在 Windows 平台上的環境設定

## 安裝 Git Bash

* 下載 [Git Bash](https://git-for-windows.github.io/)
* Windows Explorer integration 中記得勾選 **Git Bash Here**
* 其他使用預設值設定即可

## 安裝 Python

* 下載最新的 [Python](https://www.python.org/downloads/) (記得選擇第三版)
* 勾選 Add Python 3.X to PATH
* 其他使用預設值安裝即可

## 在 Git Bash 中設定 Python 的路徑

1. 開啟 .bashrc 設定檔:

```bash
dokel@DESKTOP-79I30R9 MINGW64 ~
$ vim .bashrc
```

2. 加入一個 `alias` 設定:

```bash
alias python='winpty python.exe'
```

3. 呼叫 Python 檢查是否安裝成功:

```bash
dokel@DESKTOP-79I30R9 MINGW64 ~
$ python -V
Python 3.6.3
```

## 利用 pip 安裝 jupyter

```bash
dokel@DESKTOP-79I30R9 MINGW64 ~
$ pip install jupyter
```

## 打開 jupyter notebook

```bash
dokel@DESKTOP-79I30R9 MINGW64 ~
$ jupyter notebook
```

接著 jupyter 會自動開啟瀏覽器切入到 notebook 的頁面
