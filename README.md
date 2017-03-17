WSO2 Balana Implementation
==========================

---

|  Branch | Build Status |
| :------------ |:-------------
| master      | [![Build Status](https://wso2.org/jenkins/job/wso2-balana/badge/icon)](https://wso2.org/jenkins/job/wso2-balana) |


---

This is WSO2 Balana, Then Open source XACML implemantation which supports XACML 3.0,2.0,1.1 and 1.0 versions. WSO2 Balana is based on Sun's XACML Implementation [1]. License of Sun's XACML implementation can be found at here [2]. But WSO2 Balana implementation is released under Apache2 license [3]

[1] http://sunxacml.sourceforge.net/
[2] http://sunxacml.sourceforge.net/license.txt
[3] http://www.apache.org/licenses/LICENSE-2.0


# How to USE
At first, you have to install maven.
When you can use Homebrew in balana diretiory, you should run the command below.
```
brew install maven
mvn
```
And then, it's okay to run commands below,
```
mvn test && mvn package && mvn install && mvn compile
```

Next, you change directory from balana directory to sample directory
```
chomod +x ./run.sh
./run.sh
```

In case of failure about Java, you should set the alias for $JAVA_HOME at ```~/.bashrc``` or ```~/.zshenv``` etc.
