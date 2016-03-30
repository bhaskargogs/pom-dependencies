# ```<dependencies>``` in spring security

This file tells us about dependencies in the spring security

Configuration file:
```sh
<dependencies>
  <dependency>
    <groupId>org.springframework.security</groupId>
    <artifactId>spring-security-config</artifactId>
    <version>${spring.version}</version>
    <type>jar</type>
    <scope>compile</scope>
    </dependency>

    <dependency>
    <groupId>org.springframework.security</groupId>
    <artifactId>spring-security-web</artifactId>
    <version>${spring.version}</version>
    <type>jar</type>
    <scope>compile</scope>
</dependency>
</dependencies>
```
