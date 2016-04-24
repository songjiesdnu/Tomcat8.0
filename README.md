## Abstact
This is the source code of tomcat8.0.28.

## How to run

### Method 1

run method `main` in class `org.apache.catalina.startup.Bootstrap` .

notice: you should add the following to the vmarguments

`
-Dcatalina.home=launch -Dcatalina.base=launch -Djava.endorsed.dirs=launch/endorsed -Djava.io.tmpdir=launch/temp -Djava.util.logging.manager=org.apache.juli.ClassLoaderLogManager -Djava.util.logging.config.file=launch/conf/logging.properties
`

### Method 2
run `start-tomcat8.launch`
