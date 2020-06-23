# spring-boot
maven配置：conf/setting
<mirrors>
  <mirror>
  <id>nexus-aliyun</id>
  <mirrorOf>*</mirrorOf>
  <name>Nexus aliyun</name>
  <url>http://maven.aliyun.com/nexus/content/groups/public</url>;
  </mirror>
</mirrors>
<profiles>
    <profile>
      <id>jdk-14.0.1</id>
      <activation>
        <activeByDefault>true</activeByDefault>
        <jdk>14.0.1</jdk>
      </activation>
      <properties>
        <maven.compiler.source>14.0.1</maven.compiler.source>
        <maven.compiler.target>14.0.1</maven.compiler.target>
        <maven.compiler.compilerVersion>14.0.1</maven.compiler.compilerVersion>
      </properties>
	  </profile>
</profiles>
