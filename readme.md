<h2>如何运行</h2>
		a 由于是maven项目，你的计算机得配置了maven环境，并且确保无误
		
		b 修改数据库配置文件中的相关用户名/密码，路劲 Somnus\src\main\resources\config.properties
		
		c 在你的数据库中，新建一个仓库，名字必须和jdbc.url中的一致，
			至于建表和加入用例数据，系统启动自动完成（后期会逐步完善，新建仓库也会自动化完成）
			
		d 编译项目，点击maven install.bat 编译，正确执行完，就会自动关闭cmd命令窗口
		
		e 启动jetty服务，点击maven jetty run.bat项目运行，端口默认9999

<h3>访问地址http://localhost:9999/Somnus</h3>