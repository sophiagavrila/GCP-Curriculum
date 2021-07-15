# Gradle
*Gradle is a build automation tool.  It can be used to build small or complex projects quickly.  It is written in ***Groovy*** which is a scripting language built to run on the JVM. Groovy script is compiled to Java byte-code.  The Groovy library is installed implicitly when you download Gradle.*

## Groovy Script
Apache Groovy is an object oriented and Java syntax compatible programming language built for the Java platform. This dynamic language has many features which are similar to Python, Ruby, Smalltalk, and Pero. Groovy source code gets compiled into Java Bytecode so it can run on any platform that has JRE is installed. Groovy also performs a lot of tasks behind the scene that makes it more agile and dynamic.  There are 2 key characteristics that differentiate it from Java:

    - Brackets are optional if the method has one 1 argument
    - Groovy supports closure which is like a blcok of code passed around like a variable and executed at a later point.

### Groovy `Hello World` Example
In Java, to print the string `Hello World!` we might run the following code:

```java
public class Demo {
    public static void main(String args[]) {
        System.out.println("Hello World");
    }
}
```

- The above is both valid Java, and valid Groovy. In pure Groovy, however we can do away with class creation, public method creation, etc and achieve the same output with a single line code as follows:

```groovy
println "Hello World." 
```

- Groovy supports Dynamic Typing. Variables are defined using the keyword "def," and the type of a variable does not need to be declared in advance. The compiler figures out the variable type at runtime and you can even the variable type.

```groovy
def x = 104
println x.getClass()
x = "Guru99"
println x.getClass()
```

*Output*
```groovy
class java.lang.Integer
class java.lang.String
```

> *Note: You can still declare variable types like byte, short, int, long, etc with Groovy. But you cannot dynamically change the variable type as you have explicitly declared it.*

