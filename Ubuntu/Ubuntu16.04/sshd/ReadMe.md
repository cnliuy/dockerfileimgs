## Ubuntu16.04 ����ssh����

1. ����Ҫ��ӹ��ھ���ͨ�������ƣ�evernote ���� "docker ��� ���ھ���"��

2. �л����ļ����£�ִ��shell�ű�
	$ sudo  sh  build.sh 

3. ����docker:<br>
	$ sudo docker images <br>
	REPOSITORY			TAG			IMAGE ID		CREATED		SIZE<br>
	registry:5000/library/ub16-sshd	16.04			e6d9af1c407d	About a minute ago	220.3 MB<br>
	ubuntu				16.04			f8d79ba03c00	14 hours ago		126.4 MB<br>
	hello-world			latest			c54a2cc56cbb	5 weeks ago		1.848 kB<br>

	$ sudo docker rmi f8d79ba03c00 (ɾ������)
	
	$ ���鿴�����������ϵ��
