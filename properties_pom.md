# ```<properties>``` section of pom.xml

This file consists of the versions of Spring, Apache and other related versions.

General properties with usage of Spring version:

```sh
<properties>
<project.build.sourceEncoding>UTF-8</project.build.sourceEncoding>
		<spring.version>[spring_version]</spring.version>
    </properties>
```

Properties with the usage of Apache CXF version:

```sh
<properties>
<project.build.sourceEncoding>UTF-8</project.build.sourceEncoding>
		<spring.version>[spring_version]</spring.version>
              <cxf.version>[apache_cxf_version]</cxf.version>
</properties>
```

# Note: [spring_version] and [apache_cxf_version] is dependent on the version you're using
