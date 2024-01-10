
./mvnw release:prepare -B -DreleaseVersion=1.1 -DdevelopmentVersion=1.2-SNAPSHOT -Dtag=maven-release-v1.1

./mvnw release:perform