# ΢��
��ϵͳ�ǻ���easyswoole������������ϵͳ,ʵ���˵�½���˳���ѡ�������ҡ���ĳ���������ڵ�ĳ����Ա����˽�ġ���ȫ���Ա���졣<br>
��ϵͳ�����࣬�ǳ��ʺϳ�ѧ��ѧϰswoole��easyswoole��<br>
#��������
swoole 2.x easyswoole 2.x redis3.x Mysql5.7 PHP7.1+ Nginx<br>
#��װ����:<br>
����1����װPHP����php��װswoole2.x��չ<br>
����2����װMysql��Redis��Nginx,����Ŀ¼�µ�easyswoole.sql���뵽mysql<br>
����3������Nginx<br>
����server {<br>
������client_max_body_size 8M;<br>
������listen       80;<br>
������server_name ����ĳ����Լ���IP������;<br>
������root ��Ŀ·��;<br>
������index index.html index.htm index.php;<br>
������location / {<br>
��������if (!-e $request_filename){<br>
��������������proxy_pass http://127.0.0.1:9501;<br>
������������}<br>
��������}<br>
����}<br>
����4���޸ĸ�Ŀ¼��Config.php Redis��Mysql������<br>
����5��Public/static/js/common.js�����baseUrl��Ϊ���������IP<br>
����6�������Ŀ¼ php easyswoole start ������Ŀ<br>
Ŀǰ��û�п����û�ע�Ṧ��,��������˻������Լ���wl_member������ӡ�<br>
��ʼ���˻�:18588888888��18577777777��185666666666���붼��123456<br>

#������:
�������� 11468804@qq.com<br>
  �������⣬��ӭ��Һ���һ����ѧϰ��<br>