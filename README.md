sonar-scan
==================

Wrap [SonarQube Scanner](https://docs.sonarqube.org) as a node module.

I have teste also on Angular, React & Vue.js projects

# Versions
|  version | [sonar-scanner-cli](https://mvnrepository.com/artifact/org.sonarsource.scanner.cli/sonar-scanner-cli) |
|----------|-----------------------|
|   1.0.0  |    3.1.0.1141         |
|   1.0.1  |    4.8.0.2856         |
|   latest |    6.2.1.4610         |

# Installation

This plugin requires JAVA 11 installed

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
