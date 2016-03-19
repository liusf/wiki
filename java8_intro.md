### Java 8

[What's New In JDK 8](http://www.oracle.com/technetwork/java/javase/8-whats-new-2157071.html)

#### java.util
* Base64
* Optional/OptionalInt
* Int/Long/DoubleSummaryStatistics
* Objects (jdk7)

#### java.util.concurrent
* CompletableFuture

#### java.time
SB的new Date()参数，year start at 1900, months start at 1, days start at 0

Joda-Time作者联合主导

[Jdk 8 Date and Time](http://www.oracle.com/technetwork/articles/java/jf14-date-time-2125367.html)

#### Lambda

```
//Old way:
List<Integer> list = Arrays.asList(1,2,3,4,5,6,7);
int sum = 0;
for(Integer n : list) {
    int x = n * n;
    sum = sum + x;
}
System.out.println(sum);

//New way:
List<Integer> list = Arrays.asList(1,2,3,4,5,6,7);
int sum = list.stream().map(x -> x*x).reduce((x,y) -> x + y).get();
System.out.println(sum);
```

#### stream API

#### Default methods

#### Type Annotation

#### Java 7
* try with resources
* fork/join
* 
