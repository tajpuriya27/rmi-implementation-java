
# How to run all codes?

1. Open Command prompt *[let's say cmd1]* and navigate to the folder.
    ```
    javac AddRemImpl.java
    javac AddServer.java
    ```
2. Open another Command prompt *[Let's say cmd2]* and navigate to the folder.
    ```
    javac AddRem.java
    javac addclient.java
    ```
3. In **Cmd1** 
   ```
   start rmiregistry
   java AddServer
   ```
4. In **Cmd2**
   ```
   java addclient
   ```

# What is Remote Control Interface(RMI)?


# RMI Architecture

# Is it used nowadays?

# why are we still reading it?


# Learnings while writing this code?

> Error Message: "The public type <<classname\>> must be defined in its own file"   
>>Solution:   
If .java file contains top level (not nested) public class, it has to have the same name as that public class. So if you have class like public class A{...} it needs to be placed in A.java file. Because of that we **can't have two public classes in one .java file.**


