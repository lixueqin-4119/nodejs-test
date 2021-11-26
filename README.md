<h1>启动应用:</h1>
       node server.js 8888

添加路由:
      1.编辑 server.js 文件，添加 if else
      2.重新运行 node server.js 8888
      3.每次修改记得重启  control+class=" "中断
    
后台启动应用:
          touch log node server.js 8888 >log log 2>&1 &

