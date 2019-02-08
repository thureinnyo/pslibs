$ git checkout repository

$ mvn install:install-file -DgroupId=com.platonicsoft -DartifactId=pscore -Dversion=2.0.2 -Dfile=C:/Work/projects/pscore/target/pscore-2.0.2.jar -Dpackaging=jar -DgeneratePom=true -DlocalRepositoryPath=.  -DcreateChecksum=true

$ git add -A . && git commit -m "Release 2.0.2"


### Reference from POM File ##
<repository>
	<id>ps-releases</id>
	<name>PS Releases</name>
	<url>https://raw.github.com/thureinnyo/pslibs/repository</url>
</repository>
