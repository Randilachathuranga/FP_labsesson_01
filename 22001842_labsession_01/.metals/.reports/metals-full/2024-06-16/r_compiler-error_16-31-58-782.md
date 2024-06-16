file:///C:/Users/hp/Desktop/22001842_labsession_01/2.scala
### dotty.tools.dotc.core.TypeError$$anon$1: Toplevel definition main is defined in
  C:/Users/hp/Desktop/22001842_labsession_01/1.scala
and also in
  C:/Users/hp/Desktop/22001842_labsession_01/2.scala
One of these files should be removed from the classpath.

occurred in the presentation compiler.

presentation compiler configuration:
Scala version: 3.3.3
Classpath:
<HOME>\AppData\Local\Coursier\cache\v1\https\repo1.maven.org\maven2\org\scala-lang\scala3-library_3\3.3.3\scala3-library_3-3.3.3.jar [exists ], <HOME>\AppData\Local\Coursier\cache\v1\https\repo1.maven.org\maven2\org\scala-lang\scala-library\2.13.12\scala-library-2.13.12.jar [exists ]
Options:



action parameters:
offset: 114
uri: file:///C:/Users/hp/Desktop/22001842_labsession_01/2.scala
text:
```scala

object demo {
    
    def convert(temp : Double) : Double ={
        temp * 1.8 + 32;
     }

//main 
  @@def main(args: Array[String]): Unit = {
    
    val celsiusTemperature = 35.0
    val fahrenheit = convert(celsiusTemperature);
    println();
    println("Fahrenheit is : " + fahrenheit + "'F");
    println();
    
   
  }
}
```



#### Error stacktrace:

```

```
#### Short summary: 

dotty.tools.dotc.core.TypeError$$anon$1: Toplevel definition main is defined in
  C:/Users/hp/Desktop/22001842_labsession_01/1.scala
and also in
  C:/Users/hp/Desktop/22001842_labsession_01/2.scala
One of these files should be removed from the classpath.