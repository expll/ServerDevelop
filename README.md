###### 后端开发
###### nodejs项目git仓库需要或略第三方文件夹node_modules, 可根据package.json重新安装
```
npm install
```

PM2是一个常用的Node.js进程管理工具，可以帮助您管理和监控Node.js应用程序。以下是使用PM2的基本步骤：

```
npm install pm2 -g
pm2 start index.js
pm2 list
pm2 stop <app_id>
pm2 restart <app_id>
pm2 logs <app_id>
配置自动启动：如果您希望在系统重启后自动启动您的应用程序，可以使用以下命令将应用程序配置为自动启动：
pm2 startup
```
