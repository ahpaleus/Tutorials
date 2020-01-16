This tutorial is fast break into decompiling and debugging JAR files in Eclipse. Inspired by mr_me
[Busting Cisco's Beans :: Hardcoding Your Way to Hell](https://srcincite.io/blog/2020/01/14/busting-ciscos-beans-hardcoding-your-way-to-hell.html)

1. Install Eclipse https://www.eclipse.org/downloads/
2. Install Enhanced Class Decompiler from eclipse marketplace https://marketplace.eclipse.org/content/enhanced-class-decompiler
3. Configure Enhanced Class Decompiler https://ecd-plugin.github.io/ecd/
4. Open a new project
 ![screenshots/1.png](screenshots/1.png)
5. Create a Java project
 ![screenshots/2.png](screenshots/2.png)
6. Type in Project name (in this case _Name123_) and click _Finish_
![screenshots/3.png](screenshots/3.png)
7. Just don't create module (click _Don't create_)
![screenshots/4.png](screenshots/4.png)
8. Right click on the name of the project -> _Build path_ -> _Configure build path..._
![screenshots/5.png](screenshots/5.png)
9. Add external JARs
![screenshots/6.png](screenshots/6.png)
10. Choose file from localsystem & click _Open_
You can use this easy example:  
[Helloworld_if.jar](Helloworld_if.jar)
![screenshots/7.png](screenshots/7.png)
11.  Select _Apply and Close_
12.  Just doubleclick on *.class file in Project Explore!
![screenshots/8.png](screenshots/8.png)
13. We can start debugging by rightclick on *.jar and _Debug as_
![screenshots/9.png](screenshots/9.png)
14. Here we are! _Step into_/_Step over_ and have fun
![screenshots/10.png](screenshots/10.png)