

### 安裝Step[pipenv or virtualenv]
1. install python3
2. install pip3
3. [全局安裝] install pipenv or virtualenv
4. mkdir test
> 須先創立一個專案資料夾
5. cd test
> 進入項目資料夾
6. pipenv install or pipenv install --python 3.7(選特定版本python,須先確認是否有安裝特定版本的python)
> 創建一個虛擬環境，一個專案資料夾 = 一個虛擬環境， 互相綁定且可以隔離不同的lib，易遷移
7. pipenv shell or workon xxxenv
> 啟動當前虛擬環境
8. pipenv install flask or pip install flask
> 開始安裝其他的lib
9. pipenv graph
> 查詢與環境相依的lib

10. pipenv --venv
> 查詢當前虛擬環境所在路徑

11. pip freeze