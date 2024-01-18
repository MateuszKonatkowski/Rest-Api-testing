
# Rest-Api-testing

Rest-API testing project leveraging Postman, with a focus on precision
and effectiveness in API testing. Utilized the CI/CD Newman tool to
enhance test automation and streamline workflows. The main goal of
the project was to ensure thorough API testing, validate endpoints,
and enhance the overall reliability and performance of the software
## ✳️ System Requirements 

- Install [Postman](https://www.postman.com)
- Install [Node.js](https://nodejs.org/en)
- Install [Newman](https://learning.postman.com/docs/collections/using-newman-cli/command-line-integration-with-newman/)

##  ✳️ Running Collection
#### Install Newman
```bash
  npm install -g newman
```
#### Execute newman with environment variables
```bash
  newman run <collection.json> -e <environment.json>
```
#### Generate a basic HTML report for a collection run
```bash
  newman run <collection.json> -r htmlextra
```


## ✳️ Newman
![](https://i.imgur.com/oFCXKOp.gif)

## ✳️ Report

![](https://i.imgur.com/qtxG03O.png)
## Author

- [Mateusz Konatkowski ](https://github.com/MateuszKonatkowski)

