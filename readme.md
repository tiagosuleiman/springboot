### Mount package with maven

Save your pom.xml and run mvn package from the command line:

$ mvn package


### Permission execution linux

##### in folder target

$ chmod +x springBoot-0.1.0.jar

### Verify package

If you look in the target directory you should see springBoot-0.1.0.jar. The file should be around 10 MB in size. If you want to peek inside, you can use jar tvf:

$ jar tvf target/springBoot-0.1.0.jar

### Run jar project

java -jar springBoot-0.1.0.jar