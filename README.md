> Fork 于 [shadowsocks-heroku](https://github.com/mrluanma/shadowsocks-heroku) 项目

## 部署到c9.io

1. fork 本项目

2. 在 c9.io 创建对应项目的 public workspace（尽量不要泄露个人地址）
    
   https://c9.io/account/repos, Clone to edit

3. 在 workspace 打开 terminal（快捷键 alt + t），运行
    ```
    npm install
    ```

4. 右键 server.js 点击'Run', 开始运行服务端

   ```
   Your code is running at https://shadowsocket-onplus.c9users.io.
   ```
5. 修改 ENV (推荐) 或者config.json 的密码，重新运行server.js

    ![按tab确定key-value](https://user-images.githubusercontent.com/31188782/31967727-57a57ebe-b941-11e7-8528-a9a5cb6081a6.png)

6. 客户端配置参考 [shadowsocks-heroku](https://github.com/onplus/shadowsocks-heroku#启动本地-client) 

注意：https://docs.c9.io/docs/inactive-workspaces  

### C9.IO仅供学习使用
