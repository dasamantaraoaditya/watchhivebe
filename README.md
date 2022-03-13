# watchhivebe
Watch-Hive backend-code goes in here.


## Important Links
* Backend: https://github.com/dasamantaraoaditya/watchhivebe
* FrontEnd: https://github.com/dasamantaraoaditya/watchhivefe
* Docs: https://github.com/dasamantaraoaditya/watchhivefe/wiki
* TaskTracking:https://github.com/users/dasamantaraoaditya/projects/2 
* Slack Channel : https://watch-hive.slack.com/

## Configurations preferred for watchhivebe
1) Make sure you have JDK 8 or 11. (JDK 8 is preffered)
2) A perfect IDE is preferred (Intellij comes into picture).
3) Make sure we have latest version of maven installed in the system.
4) Adding mvn and jdk in your path variables, preffarable link.
     https://mkyong.com/java/how-to-set-java_home-environment-variable-on-mac-os-x/

## How to make watchhivebe alive
1) mvn clean install -DskipTests (compiles the project and makes everything ready for running it).
     For more info pls google mvn.
     Whenever we do "mvn clean install", there will be a .jar file generated in your target folder.
2) java -jar target/watchhive-0.0.1-SNAPSHOT.jar
     java -jar command helps to run your application
     "java -jar target/watchhive-0.0.1-SNAPSHOT.jar" is running our .jar generated from our mvn command.

