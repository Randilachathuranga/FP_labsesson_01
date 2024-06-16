file:///C:/Users/hp/Desktop/22001842_labsession_01/4.scala
### dotty.tools.dotc.core.TypeError$$anon$1: Toplevel definition main is defined in
  C:/Users/hp/Desktop/22001842_labsession_01/3.scala
and also in
  C:/Users/hp/Desktop/22001842_labsession_01/4.scala
One of these files should be removed from the classpath.

occurred in the presentation compiler.

presentation compiler configuration:
Scala version: 3.3.3
Classpath:
<HOME>\AppData\Local\Coursier\cache\v1\https\repo1.maven.org\maven2\org\scala-lang\scala3-library_3\3.3.3\scala3-library_3-3.3.3.jar [exists ], <HOME>\AppData\Local\Coursier\cache\v1\https\repo1.maven.org\maven2\org\scala-lang\scala-library\2.13.12\scala-library-2.13.12.jar [exists ]
Options:



action parameters:
offset: 333
uri: file:///C:/Users/hp/Desktop/22001842_labsession_01/4.scala
text:
```scala
object BookCostCalculator {

  def totalWholesaleCost(copies: Int): Double = {
    val coverPrice = 24.95
    val discount = 0.40
    val discountedPrice = coverPrice * (1 - discount)
    
    val bookCost = discountedPrice * copies;
 
   val shippingCost = if(copies <= 50){
     return  3.0;
   }else{
        return 3.@@ + (0.75 * (copies - 50)) ;
   }
    
    bookCost + shippingCost
  }

  // Main method
  def main(args: Array[String]): Unit = {
    val numberOfCopies = 60
    val totalCost = totalWholesaleCost(numberOfCopies)
    println();
    println(s"The total wholesale cost for $numberOfCopies copies is Rs. $totalCost")
    println();
    }
}



```



#### Error stacktrace:

```

```
#### Short summary: 

dotty.tools.dotc.core.TypeError$$anon$1: Toplevel definition main is defined in
  C:/Users/hp/Desktop/22001842_labsession_01/3.scala
and also in
  C:/Users/hp/Desktop/22001842_labsession_01/4.scala
One of these files should be removed from the classpath.