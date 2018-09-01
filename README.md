## Steps to Create Java Project using Maven

1. mvn archetype:generate -DgroupId=com.mycompany.app -DartifactId=my-app -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false
1. mvn package
1. java -cp target/my-app-1.0-SNAPSHOT.jar com.mycompany.app.App (Run Project)
