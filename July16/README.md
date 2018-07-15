# Hello, World !
1. **Installing Kotlin in Command Line** : An easier way to install Kotlin on UNIX based systems such as OS X, Linux, Cygwin, FreeBSD and Solaris is by using SDKMAN!. Simply run the following in a terminal and follow any instructions,
`$ curl -s https://get.sdkman.io | bash`
Next open a new terminal and install Kotlin with :
`$ sdk install kotlin`

2. **Creating and running a first application**: 
- Create a simple application in Kotlin that displays Hello, World!. Using our favorite editor, we create a new file called hello.kt with the following:
```
fun main(args: Array<String>) {
    println("Hello, World!")
}
```
- Compile the application using the Kotlin compiler
`$ kotlinc hello.kt -include-runtime -d hello.jar`
The `-d` option indicates what we want the output of the compiler to be called and may be either a directory name for class files or a *.jar* file name. The `-include-runtime` option makes the resulting *.jar* file self-contained and runnable by including the Kotlin runtime library in it. If you want to see all available options run, ` kotlinc help `.
- Run the application : `$ java -jar hello.jar`


2. **Installing/Working using Intellij IDEA** :