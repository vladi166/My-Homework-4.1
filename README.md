Филлип, добрый день. Не совсем понятно что вы имеете ввиду под тем, что тесты не проходят. Прикрепляю логи и скриншот свое работы.
# Логи
<details>
<summary>mvn clean test</summary>

```txt
C:\Users\vladi\.jdks\corretto-11.0.25\bin\java.exe "-Dmaven.multiModuleProjectDirectory=C:\Users\vladi\My Homework 4.1" -Djansi.passthrough=true "-Dmaven.home=C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2024.2.4\plugins\maven\lib\maven3" "-Dclassworlds.conf=C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2024.2.4\plugins\maven\lib\maven3\bin\m2.conf" "-Dmaven.ext.class.path=C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2024.2.4\plugins\maven\lib\maven-event-listener.jar" "-javaagent:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2024.2.4\lib\idea_rt.jar=59847:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2024.2.4\bin" -Dfile.encoding=UTF-8 -classpath "C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2024.2.4\plugins\maven\lib\maven3\boot\plexus-classworlds-2.8.0.jar;C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2024.2.4\plugins\maven\lib\maven3\boot\plexus-classworlds.license" org.codehaus.classworlds.Launcher -Didea.version=2024.3 clean test
[INFO] Scanning for projects...
[INFO] 
[INFO] ------------------< ru.netology.javaqa:MyHomework4.1 >------------------
[INFO] Building MyHomework4.1 1.0-SNAPSHOT
[INFO]   from pom.xml
[INFO] --------------------------------[ jar ]---------------------------------
[INFO] 
[INFO] --- clean:3.2.0:clean (default-clean) @ MyHomework4.1 ---
[INFO] Deleting C:\Users\vladi\My Homework 4.1\target
[INFO] 
[INFO] --- checkstyle:3.2.1:check (validate) @ MyHomework4.1 ---
[INFO] You have 0 Checkstyle violations.
[INFO] 
[INFO] --- resources:3.3.1:resources (default-resources) @ MyHomework4.1 ---
[INFO] Copying 0 resource from src\main\resources to target\classes
[INFO] 
[INFO] --- compiler:3.13.0:compile (default-compile) @ MyHomework4.1 ---
[INFO] Recompiling the module because of changed source code.
[INFO] Compiling 2 source files with javac [debug target 11] to target\classes
[INFO] 
[INFO] --- resources:3.3.1:testResources (default-testResources) @ MyHomework4.1 ---
[INFO] skip non existing resourceDirectory C:\Users\vladi\My Homework 4.1\src\test\resources
[INFO] 
[INFO] --- compiler:3.13.0:testCompile (default-testCompile) @ MyHomework4.1 ---
[INFO] Recompiling the module because of changed dependency.
[INFO] Compiling 1 source file with javac [debug target 11] to target\test-classes
[INFO] 
[INFO] --- surefire:3.2.5:test (default-test) @ MyHomework4.1 ---
[INFO] Using auto detected provider org.apache.maven.surefire.junitplatform.JUnitPlatformProvider
[INFO] 
[INFO] -------------------------------------------------------
[INFO]  T E S T S
[INFO] -------------------------------------------------------
[INFO] Running BonusServiceTest
[INFO] Tests run: 4, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 0.031 s -- in BonusServiceTest
[INFO] 
[INFO] Results:
[INFO] 
[INFO] Tests run: 4, Failures: 0, Errors: 0, Skipped: 0
[INFO] 
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  3.185 s
[INFO] Finished at: 2024-11-21T14:22:43+05:00
[INFO] ------------------------------------------------------------------------

Process finished with exit code 0
```
</details>

# Скриншот

![Снимок экрана 2024-11-21 142734](https://github.com/user-attachments/assets/f12664fd-89b2-48fa-9028-1613817ffc48)
