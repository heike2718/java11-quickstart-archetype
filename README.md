# java11-quickstart-archetype

creates a simple java-11 project with JUnit5, slf4j and owasp dependency-check plugin

## Install into local maven repo

	git clone https://github.com/heike2718/java11-quickstart-archetype.git
	cd java11-quickstart-archetype
	mnv clean install

## Create new java-11-project

	mvn archetype:generate -DarchetypeGroupId=de.egladil.maven -DarchetypeArtifactId=java11-quickstart-archetype -DarchetypeVersion=1.0.0-SNAPSHOT -DgroupId=de.egladil.web -DartifactId=archetype-test -DinteractiveMode=false


