# SyBase Spring Configuration

jConnect JDBC Driver is not a maven project.

Add to local maven repository Jconnect.

mvn install:install-file -Dfile=YourJConnectFilePath\jconnect.jar -DgroupId=com.sybase.jdbc4.jdbc  -DartifactId=sybase-jconnect -Dversion=1.6.0 -Dpackaging=jar

Happy coding.
