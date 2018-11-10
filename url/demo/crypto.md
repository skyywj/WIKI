### 加解密服务

github地址：https://github.com/skyywj/CryptoService.git

接口地址：https://github.com/skyywj/Dubbo-Service-API/blob/master/src/main/java/com/sky/hypro/service/tools/CryptoService.java

主要提供两个接口，在service-api中有说明：
```java
    /**
     * rsa 解密
     */
    byte[] rsaDecrypt(int cryptoScene, byte[] data);

    /**
     * rsa 加密
     */
    byte[] rsaEncrypt(int cryptoScene, byte[] data);
```
