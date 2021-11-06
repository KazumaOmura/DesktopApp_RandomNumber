# DesktopApp_RandomNumber
# py2app環境構築
py2appダウンロード
```
pip3 install py2app
```
PATHを通す
```
echo export PATH=/Users/【Username】/Library/Python/3.8/bin:$PATH' >> ~/.bash_profile
source ~/.bash_profile
```
setupファイルの作成

```
py2applet --make-setup app.py
```
setupファイルからappファイル作成

```
python3 setup.py py2app 
```
dist内のファイルを起動して実行
