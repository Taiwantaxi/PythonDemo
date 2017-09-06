# PythonDemo

---

## 部署 Heroku 必要檔案
  * requirements.txt

  * Procfile

  * runtime.txt

#### requirements.txt

Heroku 會讀取該檔案安裝您的 python 環境所需要的各種套件

可以使用 cmd (命令提示字元) 輸入以下指令查看目前電腦所安裝套件
```
pip freeze
```

然後使用以下指令匯出 requirements.txt
```
pip freeze > requirements.txt
```

#### Procfile
Profile 檔案告訴 Heroku 如何啟動該 App
```
web: python app.py
```

#### runtime.txt
runtime.txt 指定 Heroku 安裝的 Python 版本
```
python-2.7.13
```

---
## 從 Github 部署到 Heroku
> 開啟 Heroku 創建 New App 連接 Github 帳號 Deploy 專案
