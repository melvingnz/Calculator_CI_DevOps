# Calculator_CI_DevOps

1. Programming Language: Java
2. Build tool: Apache Maven
3. Source Code Management: GitHub for Git
4. Continuous Integration and Continuous Deployment: Jenkins
5. Artifact Repository Management: Sonatype Nexus

Steps:

1. Write Source Code in Java

2. Configure the project in Apache Maven
2.1. Create an Apache Maven project hierarchy using following command on the command line:
mvn archetype:generate -DgroupId=Calculator -DartifactId=Calculator_CI_DevOps -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.4 -DinteractiveMode=false
2.2. Copy our java code in the Maven hierarchy
2.3. Clean the project hierarchy using Maven on command line:
mvn clean
2.4. Compile the java source code:
mvn compile
2.5. Create a build of the project using Install goal:
mvn install
2.6. Maven Site goal:
mvn site

3. Host the project on GitHub

4. Create an automated pipeline using Jenkins
https://github.com/melvingnz/Calculator_CI_DevOps/blob/57c34eb9913d1ecd02109082a0d5bfb2b49743b1/Create%20an%20automated%20pipeline%20using%20Jenkins.png
5. Creating an automated Pipeline for our project using Jenkins

6. Deploy the build artifacts to Nexus repository via Jenkins
