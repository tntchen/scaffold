# 服务管理-调度服务
http://blog.didispace.com/spring-boot-run-backend/
## 以脚本管理
+ start.sh 
启动服务
+ stop.sh
关闭服务 
+ restart.sh
重启服务

## 以系统服务进行管理


sudo ln -s /xxx/xxx/perye-scheduling.jar /etc/init.d/perye-scheduling
	
/etc/init.d/perye-scheduling start|stop|restart
