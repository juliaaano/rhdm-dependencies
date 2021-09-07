# RHDM Dependencies

**This project is deprectated. Use project [RHPAM Dependencies](https://github.dev/juliaaano/rhpam-dependencies) instead.**

---

Red Hat Decision Manager POM dependencies.

## Use as a parent in pom.xml
```xml
<parent>
    <groupId>com.juliaaano</groupId>
    <artifactId>rhdm-dependencies</artifactId>
    <version>1.0.3</version>
</parent>
```

## Use as an import in pom.xml
```xml
<dependencyManagement>
    <dependencies>
        <dependency>
            <groupId>com.juliaaano</groupId>
            <artifactId>rhdm-dependencies</artifactId>
            <version>1.0.3</version>
            <type>pom</type>
            <scope>import</scope>
        </dependency>
    </dependencies>
</dependencyManagement>
```
