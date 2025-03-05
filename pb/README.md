#### pocketbase安装包下载地址download 
    https://github.com/pocketbase/pocketbase/releases/download/v0.23.4/

```bash
cd pb

xattr -d com.apple.quarantine pocketbase # 赋予pocketbase应用程序可执行权限（macOS）

./pocketbase migrate up # for first run

./pocketbase --dev superuser create "test@example.com" "1234567890" # If you don't have an initial account, please use this command to create it

./pocketbase serve # 启动pocketBase数据库

```


####  Web 管理面板，地址：
    http://127.0.0.1:8090/
