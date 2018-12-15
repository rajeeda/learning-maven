# learning-maven
maven experiments


Maven notes

/usr/local/Cellar/maven/3.6.0/libexec/conf/Settings file

Understand what are lifecycles

Life cycle includes phases

Phases include goals

Test phases implies compile phase
testCompile is a goal

Define compiler version

<plugin>
            <groupId>org.apache.maven.plugins</groupId>
            <artifactId>maven-compiler-plugin</artifactId>
            <version>3.2</version>
            <configuration>
                <source>1.8</source>
                <target>1.8</target>
            </configuration>
        </plugin>

Or 

<maven.compiler.source>1.6</maven.compiler.source> 
	<maven.compiler.target>1.6</maven.compiler.target>

Source encoding 
    <project.build.sourceEncoding>UTF-8</project.build.sourceEncoding> 

Maven -X compile for debug output

Man -DskipTests tests

Desktop local pgsql user password 1234
