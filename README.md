# project1
my personer project
生成密钥
ssh-keygen -t rsa -P '' -f ~/.ssh/id_rsa
cat ~/.ssh/id_rsa.pub >> ~/.ssh/authorized_keys
chmod 0600 ~/.ssh/authorized_keys

ssh权限
scp ~/.ssh/id_rsa.pub root@zoo1:~/.ssh/key_from_zoo1
10分钟建立hbase与elasticsearch连接
http://lessc0de.github.io/connecting_hbase_to_elasticsearch.html
