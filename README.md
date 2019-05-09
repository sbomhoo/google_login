# google_login
구글 login API , OAUTH 2.0으로 인증

-------------

![날씨3](./이미지11.png)  
  
# pom.xml 추가할 내용 
```java 
 <!-- Google Login -->
        <dependency>
            <groupId>org.springframework.social</groupId>
            <artifactId>spring-social-google</artifactId>
            <version>1.0.0.RELEASE</version>
        </dependency>
 
 
    	<dependency>
            <groupId>org.apache.httpcomponents</groupId>
            <artifactId>httpclient</artifactId>
            <version>4.5.3</version>
        </dependency>
        
        <!-- https://mvnrepository.com/artifact/com.fasterxml.jackson.core/jackson-core -->
		<dependency>
		    <groupId>com.fasterxml.jackson.core</groupId>
		    <artifactId>jackson-core</artifactId>
		    <version>2.9.8</version>
		</dependency>
``` 

# MappingJackson2HttpMessageConverter 에러 나면  
https://bumcrush.tistory.com/150


# 참고 블로그  
https://gdtbgl93.tistory.com/73  
