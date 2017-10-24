> Fork 于 [shadowsocks-heroku](https://github.com/mrluanma/shadowsocks-heroku) 项目

## 部署到c9.io

1. fork 本项目

2. 在 c9.io 创建对应项目的 workspace
    
   https://c9.io/account/repos, Clone to edit

3. 在 workspace 打开 terminal（快捷键 alt + t），运行
    ```
    npm install
    ```
4. 修改服务端 config.json 中的'password'

    如果是public workspace，建议在ENV中配置

    ![image](https://user-images.githubusercontent.com/31188782/31967727-57a57ebe-b941-11e7-8528-a9a5cb6081a6.png)

5. 右键 server.js 点击'Run', 开始运行服务端

   ```
   Your code is running at https://shadowsocket-onplus.c9users.io.
   ```

6. 客户端配置参考 [shadowsocks-heroku](https://github.com/onplus/shadowsocks-heroku#启动本地-client) 

注意：https://docs.c9.io/docs/inactive-workspaces  仅供学习使用
