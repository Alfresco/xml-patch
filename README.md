# XML Patch

Nothing new, just a runnable JAR that embeds https://github.com/dnault/xml-patch

## Create Runnable JAR
```
mvn assembly:assembly
```

## Run
```
java -jar /Users/mau/w/xml-patch/target/xml-patch-1.0-SNAPSHOT-jar-with-dependencies.jar sample/example.xml sample/diff.xml output.xml
```
