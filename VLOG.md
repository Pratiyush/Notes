Java 11
-----------

java.xml.bind (JAXB) - REMOVED IN JAVA 11

* Java 8 - OK
* Java 9 - DEPRECATED
* Java 10 - DEPRECATED
* Java 11 - REMOVED

See JEP 320 for more info. (JEP - JDK Enhancement Proposal)

Use Below dependencies to use JAXB to generate models:

```xml
	<dependencies>
		<dependency>
			<groupId>com.sun.xml.bind</groupId>
			<artifactId>jaxb-core</artifactId>
			<version>3.0.2</version>
		</dependency>
		<dependency>
			<groupId>com.sun.xml.bind</groupId>
			<artifactId>jaxb-impl</artifactId>
			<version>3.0.2</version>
		</dependency>
	</dependencies>
 ```
 s
