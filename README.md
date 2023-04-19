sonar-scan
==================

Wrap [SonarQube Scanner](https://docs.sonarqube.org/display/SCAN/Analyzing+with+SonarQube+Scanner) as a node module.

# Installation

This plugin requires JAVA runtime installed

You can install sonar-scan as a development dependency and add it as a script property in your package.json.

```shell
npm i sonar-scan --save-dev
```     

```json
{
  "scripts": {
    "sonar-scan": "node_modules/sonar-scan/bin/sonar-scanner"
  }
}
```

```shell
npm run sonar-scan
```     
# Forked from

https://github.com/bcaudan/node-sonar-scanner

This library is not updated currentlly for a few years but we need & support it
