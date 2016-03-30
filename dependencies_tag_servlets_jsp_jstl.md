# ```<dependencies>``` of Tag libraries, servlets, JSP and JSTL

This file consists of the various ```<dependencies>``` of Tag libraries, servlets, JSPs and JSTL.

The configuration of the files is as follows:

```sh

<dependencies>
    	
    	<!-- Dependencies for tag libraries, servlets , JSP and JSTL -->
    	<dependency>
		<groupId>taglibs</groupId>
		<artifactId>standard</artifactId>
		<version>1.1.2</version>
	</dependency>

	<dependency>
		<groupId>javax.servlet</groupId>
		<artifactId>servlet-api</artifactId>
		<version>2.5</version>
		<scope>provided</scope>
	</dependency>

	<dependency>
		<groupId>javax.servlet</groupId>
		<artifactId>jsp-api</artifactId>
		<version>2.0</version>
		<scope>provided</scope>
	</dependency>

	<dependency>
		<groupId>javax.servlet</groupId>
		<artifactId>jstl</artifactId>
		<version>1.2</version>
	</dependency>
</dependencies>
```
