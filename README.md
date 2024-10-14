# [core-parent](https://github.com/kevinxjavier/core-parent.git)

## Pom parent for SpringBoot projects

##### Software Requirements:
* Apache Maven 3.8.6
* Java 18.0.2.1
* Spring-boot 3.3.4
* Tested on Debian GNU/Linux 9 (stretch)
 
##### Run
`mvn clean install` on the root `pom.xml` to install library in your `.m2`

##### Usage
If you use only library, configure pom in your SpringBoot project:

 ```xml
	<parent>
		<groupId>com.kevinpina</groupId>
		<artifactId>core-parent</artifactId>
		<version>0.0.1-SNAPSHOT</version>
		<relativePath/>
	</parent>
```

##### Contact

| User    | Name                     | Role       |
|:--------|:-------------------------|:-----------|
| kpina   | Kevin Javier Piña        | Developer  |
