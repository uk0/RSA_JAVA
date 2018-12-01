## RSA 数字签名


  * 私钥签名 
  * 公钥验签
  
  
  

```java

RSA.sign(body,key)

```

## demo

```java
/**
* 签名的时候注意，签名时候charset 一定要协商好
* */

RSA.sign(inJsonStr.getBytes("GBK"), config.PRIVATEKEY);
```


### Time
  * 2018年12月01日20:02:21

