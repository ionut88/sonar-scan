sonar-scan
==================

Wrap [SonarQube Scanner](https://docs.sonarqube.org) as a node module.

I have teste also on Angular, React & Vue.js projects

# Versions
|  version | [sonar-scanner-cli](https://mvnrepository.com/artifact/org.sonarsource.scanner.cli/sonar-scanner-cli) |
|----------|-----------------------|
|   latest |    8.0.0.6341   	     |
|   1.0.6  |    7.3.0.5189   	     |
|   1.0.5  |    7.2.0.5079   	     |


# Installation

This plugin requires JAVA 17 or later installed

You can install sonar-scan as a development dependency and add it as a script property in your package.json.

```shell
npm i sonar-scan --save-dev
```     

Node:
```json
{
  "scripts": {
    "sonar-scan": "node_modules/sonar-scan/bin/sonar-scanner"
  }
}
```
Angular, React & Vue.js projects:
```json
{
  "scripts": {
    "sonar-scan": "sonar-scanner"
  }
}
```

```shell
npm run sonar-scan
```     
# Forked from

https://github.com/bcaudan/node-sonar-scanner

This library is not updated for a few years but we need & support it
