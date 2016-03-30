# ```<plugins>``` in pom.xml

This file is independent of the dependencies. It follows the ```<finalName>```
component of the pom.xml file and reside in the ```<build>``` functionality

The configuration part is as follows:

```sh
<build>
		<finalName>[project name]</finalName>
		<plugins>
			<plugin>
				<groupId>org.apache.maven.plugins</groupId>
				<artifactId>maven-compiler-plugin</artifactId>
				<version>2.0.2</version>
				<configuration>
					<source>1.7</source>
					<target>1.7</target>
				</configuration>
			</plugin>
			<plugin>
				<groupId>org.apache.maven.plugins</groupId>
				<artifactId>maven-eclipse-plugin</artifactId>
				<configuration>
					<downloadSources>true</downloadSources>
				</configuration>
			</plugin>
		</plugins>
	</build>
</project>
```
### Note: [project name] is based on the name of the project 
