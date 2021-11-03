# springsecurity
## 一.注销功能：
### 1. config:
/* / 是代表首页的意思 */
http.logout().logoutSuccessUrl("/");     
![Y7J5N 7C$C RYK`@)4_ATHD](https://user-images.githubusercontent.com/47177498/139804089-b873da99-752e-4815-b760-d5e732080508.png)

### 2. index.html:
![9U 7{7P9SS_UT0 E8M`9M C](https://user-images.githubusercontent.com/47177498/139803542-d5776302-5d74-459c-bc3e-941e8d93b3ab.png)

### 3.导入themeleaf和springsecurity整合包：
![S6XQBGXH`9ACR}3B2 AAC{P](https://user-images.githubusercontent.com/47177498/139804289-3d5f3f2b-467e-4956-9560-a74a0c725ac7.png)

### 4.登录注销功能（前端）：
![~G%2~1C3XH7_WOZ$HFXC3V1](https://user-images.githubusercontent.com/47177498/139809156-8f4b1f87-412c-491d-815f-deb03ae9d282.png)

### 5.防止网站攻击：
![(P_D5@08VWFI{13T)((LH{0](https://user-images.githubusercontent.com/47177498/139809252-490960b8-4ffa-4727-bc00-ffa65cc928a7.png)

## 二 .权限控制：vip1只能进入vip1的页面
![PXX0W_XF)14~H)CMQSHNV1C](https://user-images.githubusercontent.com/47177498/139809544-f4e2b1b8-de21-47fd-91ee-ac1f00f7e73c.png)
![T)Q}TDFM9A`Y3`QK)PB_2GO](https://user-images.githubusercontent.com/47177498/139809690-b48ee2c9-3706-4c73-a591-58c9e8e43145.png)

## 三、记住我功能 
   保存在cookie里面 默认保存两周
![ULB`X8YO(`~`9%9OW}Y)3@P](https://user-images.githubusercontent.com/47177498/139810620-8077ef6e-2415-4b7f-aadc-04ad35e79f51.png)

  
## 四、页面定制

### 1. 登录页面

![%C)VX~_@T%5ABK0PKO`$I](https://user-images.githubusercontent.com/47177498/139815876-fb6b43ad-5f19-4d5b-92ee-efe023d0d79d.png)
![5VL(G}@ GCS2B`@RKJ6FI1W](https://user-images.githubusercontent.com/47177498/139815959-d1a625e2-e371-4ec9-b227-414cb5ece6dc.png)
登录请求进入toLogin页面，使用loginProcessingUrl（）方法，实际进入login页面
或者可以更改图1的login变成toLogin，后面就不用loginProcessingUrl（）方法更改页面。

![I88XGA7}U}5S P$@10MUR 7](https://user-images.githubusercontent.com/47177498/139816367-eab31529-4adb-4aab-9bbf-9705f4cd71c3.png)

默认是username，password
![9KFT_LP4ONYX6409ER4BZVQ](https://user-images.githubusercontent.com/47177498/139816410-07c48abf-dda4-4722-87c0-d83578d1fc0c.png)
前端是user .  pwd 
![KSV78K683_LK))81D0GZ0KD](https://user-images.githubusercontent.com/47177498/139816541-c30aef19-8c46-4e0c-9046-f2758eb6b324.png)
所以直接更改换成自己写的user和pwd
或者可以直接把前端名字改成默认的  下图圈中就不用写了
![I88XGA7}U}5S P$@10MUR 7](https://user-images.githubusercontent.com/47177498/139816713-7d9e4946-31f0-4329-a773-bc5ce1e85120.png)

### 2.页面定制后的记住我功能

![K%SX3$LJDODJ ){X$S4JBH2](https://user-images.githubusercontent.com/47177498/139817992-597ba9ce-f8b0-43e8-9013-543ad14377a9.png)

![6RC{772ZMB_ T$%`BP1HGPI](https://user-images.githubusercontent.com/47177498/139817915-bebceb78-4bc6-4866-bd81-dfd415d1c9b2.png)

![05NM}}JVF3FS1%)J@VBMT7V](https://user-images.githubusercontent.com/47177498/139818026-91db1960-52a6-48d1-8508-ebd4e815ab23.png)

### 3.最终首页：
![(GG)Q TO% QB)7(MNDGSJ)W](https://user-images.githubusercontent.com/47177498/139818173-eb94c266-9f40-44db-b03c-b07237b87043.png)

# Shiro
### 1. 快速入门
   Shiro是一个java安全框架。不仅可以用再javaSE，还可以在javaEE环境。

### 2.有那些功能？
![5%L7PKN~{YY8P{5W7AG~}KQ](https://user-images.githubusercontent.com/47177498/140006163-4b3bf426-6603-438b-8804-faefd66598b9.png)

### 3.Shiro框架（外部）
![)@2YIIY0{IMT2U3FTR0D($X](https://user-images.githubusercontent.com/47177498/140006287-a764b6c1-94e2-446f-9062-250fc10d333e.png)
（内部）
![~OFZM F0JBFH8{VC9BG3%_E](https://user-images.githubusercontent.com/47177498/140006344-7b61825d-b821-4b8a-a330-45872a34b151.png)

### 4.HelloWorld
![LGHUJ_PF%GD2 21TSXR1AG3](https://user-images.githubusercontent.com/47177498/140008127-2a928006-d8af-4518-ae30-7842cd249964.png)
导入shiro依赖   去maven  repository官网添加shiro-core版本号  添加log4j的配置文件

![]( https://github.com/apache/shiro/tree/main/samples/quickstart"shrio-core")
![]( https://mvnrepository.com/artifact/org.apache.shiro/shiro-core"shrio-core")



