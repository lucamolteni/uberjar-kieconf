How to run the reproducer

`mvn clean install`

`jar -tf target/uberjar-kieconf-1.0-SNAPSHOT-uber.jar`

To see the content of the kie.conf file

`unzip -p target/uberjar-kieconf-1.0-SNAPSHOT-uber.jar "META-INF/kie.conf"`
