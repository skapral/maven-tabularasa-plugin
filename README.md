# maven-tabularasa-plugin

[![Build Status](https://img.shields.io/travis/skapral/maven-tabularasa-plugin/master.svg)](https://travis-ci.org/skapral/maven-tabularasa-plugin)

Maven plugin, which introduces new packaging, `tabularasa`, with totally empty lifecycle bindings. 
Useful for the projects where precise control over bindings is required.

## Quick start

1. Add the plugin to your `pom.xml`
```
<build>
    <plugins>
        <plugin>
            <groupId>com.github.skapral</groupId>
            <artifactId>maven-tabularasa-plugin</artifactId>
            <version>0.0.0-SNAPSHOT</version>
            <extensions>true</extensions>
        </plugin>
    </plugins>
</build>
```

2. Apply packaging
```
<packaging>tabularasa</packaging>
```

3. Start managing your lifecycle bindings.
