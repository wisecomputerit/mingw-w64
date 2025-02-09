
D:\javaJar\Ecpay\javax.servlet-3.0.0.v201112011016.jar


mvn install:install-file -Dfile="D:\javaJar\Ecpay\javax.servlet-3.0.0.v201112011016.jar" -DgroupId=com.Ecpay -DartifactId=Ecpay-log4j-core -Dversion=1.0.0 -Dpackaging=jar

mvn install:install-file -Dfile="D:\javaJar\Ecpay\log4j-api-2.17.1.jar" -DgroupId=com.Ecpay -DartifactId=Ecpay-log4j-core -Dversion=1.0.0 -Dpackaging=jar

mvn install:install-file -Dfile="D:\javaJar\Ecpay\log4j-core-2.17.1.jar" -DgroupId=com.Ecpay -DartifactId=Ecpay-log4j-core -Dversion=1.0.0 -Dpackaging=jar

<!-- 引入 Ecpay-log4j-core 這個自定義安裝的 JAR -->
<dependency>
<groupId>com.Ecpay</groupId>
<artifactId>Ecpay-log4j-core</artifactId>
<version>1.0.0</version>
<scope>compile</scope>
</dependency>
<!-- 引入其他需要的依賴，例如 Log4j -->
<dependency>
<groupId>org.apache.logging.log4j</groupId>
<artifactId>log4j-api</artifactId>
<version>2.17.1</version>
</dependency>

<dependency>
<groupId>org.apache.logging.log4j</groupId>
<artifactId>log4j-core</artifactId>
<version>2.17.1</version>
</dependency>
