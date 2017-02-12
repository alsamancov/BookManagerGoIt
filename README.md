"# BookManagerGoIt"

You can create a quick start Java web application project by using Maven

$ mvn archetyp:generate -DgroupId={project-packaging}
    -DartifactId={project-name}
    -DarchetypeArtifactId=maven-archetype-webapp
    -DinteractiveMode=false

//for example
$ mvn archetype:generate -DgroupId=net.proselyte
    -DartifactId=BookManager
    -DarchetypeArtifactId=maven-archetype-webapp
    -DinteractiveMode=false
