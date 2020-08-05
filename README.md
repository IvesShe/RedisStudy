# Redis Study
學習之後，製作成筆記，方便日後使用時復習

# 在Linux 安裝 Redis
1、下載安裝包
 ![image](./images/20200804205241.png)
 ![image](./images/20200804205819.png)

```shell
mv redis-6.0.6.tar.gz /opt
cd /opt
ls
tar -zxvf redis-6.0.6.tar.gz 
```

 ![image](./images/20200804210126.png)
 ![image](./images/20200804210342.png)

 ![image](./images/20200804210521.png)

```shell
yum install gcc-c++
```
 ![image](./images/20200804210632.png)
 ![image](./images/20200804210748.png)

```shell
make
```
**這裡因為下載最新版的6.0.6的版本，make之後報錯無法解決，有重新安裝回至5.0.8的版本**
 ![image](./images/20200804212017.png)

```shell
make install
```
 ![image](./images/20200804212325.png)

redis的默認安裝路徑 usr/local/bin
 ![image](./images/20200804212503.png)

拷貝一份配置文件，確保原配置文件的安全
 ![image](./images/20200804212819.png)

開啟配置文件
 ![image](./images/20200804213241.png)

修改配置文件
 ![image](./images/20200804212819.png)

通過指定的配置文件啟動
 ![image](./images/20200804213707.png)

使用redis客戶端連接
 ![image](./images/20200804214001.png)

查看redis是否開啟
 ![image](./images/20200804214210.png)

關閉redis
 ![image](./images/20200804214356.png)

再次查看redis是否開啟
 ![image](./images/20200804214422.png)