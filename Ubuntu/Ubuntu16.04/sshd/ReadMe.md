## Ubuntu16.04 附带ssh服务

1. 如需要添加国内镜像，通过阿里云（evernote 搜索 "docker 添加 国内镜像"）

2. 切换到文件夹下，执行shell脚本
	$ sudo  sh  build.sh 

3. 操作docker:<br>
	$ sudo docker images <br>
	REPOSITORY			TAG			IMAGE ID		CREATED		SIZE<br>
	registry:5000/library/ub16-sshd	16.04			e6d9af1c407d	About a minute ago	220.3 MB<br>
	ubuntu				16.04			f8d79ba03c00	14 hours ago		126.4 MB<br>
	hello-world			latest			c54a2cc56cbb	5 weeks ago		1.848 kB<br>

	$ sudo docker rmi f8d79ba03c00 (删除镜像)
	
	$ （查看镜像的依赖关系）
