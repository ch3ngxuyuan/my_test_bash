# my_test_bash


secure_ssh.sh
https://www.cnblogs.com/emanlee/p/10343542.html
多次失败登录即封掉IP，防止暴力破解的脚本，超过20次的就加到黑名单
创建记录登录失败次数的文件 
touch /usr/local/bin/black.txt
添加定时 10分钟执行一次   ( 定时 10分钟执行详见： https://www.cnblogs.com/emanlee/p/10293762.html )
 */10 * * * * root  sh /usr/local/bin/secure_ssh.sh
 
 
 
 
 
