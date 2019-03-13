 
 在当前目录下生成用户名密码
 docker run --entrypoint htpasswd registry:2 -Bbn testuser testpassword > ./auth/htpasswd
 
 
 用户名：testuser
 密码：testpassword