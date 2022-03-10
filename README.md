# Grails Web Profile

A profile for creating Grails Modular Monolith web applications.

## Grails Version

- Grails **5.0.0**

## Usage


### Build Profile

```
git clone https://github.com/rainboyan/web-modular.git
cd web-clean
./gradlew publishToMavenLocal
```

### Create App

#### Use Tomcat with default features

```
grails create-app --profile org.grails.profiles:web-modular:5.0.0-SNAPSHOT org.grails.demo.web-modular-demo
cd web-modular-demo
./gradlew :app:bootRun
```

## What's New

### 5.0.0-SNAPSHOT

* Update Grails 5.0

## Links

- [Grails](https://grails.org)
- [Grails Github](https://github.com/grails)
- [Grails Web Bootstrap Profile](https://github.com/rainboyan/web-bootstrap)
- [Grails Web Clean Profile](https://github.com/rainboyan/web-clean)
