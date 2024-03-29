# HOMEWORK 2 ARSW (OO Design)

Write a program to calculate the mean and standard deviation of a set of n real numbers.

# LOC/H

1. 6:00 pm - 10:00 pm - fueron en total  172 LOC
2. 10:00 am - 11:40 pm - fueron en total  143 LOC
3. Total LOC (315/17) =  18 LOC

# DESIGN
![Design](img/design.PNG)

# TEST REPORT
![Test1](img/test1.PNG)
![Test2](img/test2.PNG)
![Test3](img/test3.PNG)

## TOTAL TEST
![fullTest](img/fullTest.PNG)

# START

Copy the project through git clone in any direction to start working:
```
git clone git@github.com:Jaime107/meanStandarDeviationApp.git
```

## PRE-REQUISITES

* Java jdk > 7
* Maven (Apache Maven)
* Git

## INSTALL

1. Run in terminal:

```
$$ mvn package
```
2.(Optional):
If you want to view the documentation of the application, execute the following command and check the following path: root / target:

```
mvn javadoc:javadoc
```

3. (Run):
The following command must be used in the project root folder:
  
```
java -cp target/DeviationStandartApp-1.0-SNAPSHOT edu.escuelaing.arsw.deviationstandart.app.App src/test/resources/ProxySize.txt
```

```
java -cp target/DeviationStandartApp-1.0-SNAPSHOT edu.escuelaing.arsw.deviationstandart.app.App src/test/resources/DevelopmentHours.txt
```

![Proyecto](img/1.PNG)
  

## BUILT

* [Maven](https://maven.apache.org/) - Dependency Management
* [JAVA JDK 8](http://www.oracle.com/technetwork/java/javase/overview/index.html) - Building
* [JUnit 3.8.1](https://mvnrepository.com/artifact/junit/junit/3.8.1) - Test


## AUTHOR

* **JAIME MARTINEZ SOSA** - [Jaime107](git@github.com:Jaime107)


## LICENSE

This project is licensed under the GNU General Public License - [LICENSE](LICENSE) 