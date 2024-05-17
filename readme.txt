Both folders "1" and "2" have the same files, but
a different folder structure.



Experiment 1
============
1. Navigate to folder "1"
2. Run "mvn package"

A target folder is created

3. Navigate to the "target" folder
4. Inspect the contents of the JAR

There are no class files.

5. Navigate back to "1"
6. Run "mvn clean"


Experiment 2
============
1. Navigate to folder "2"
2. Run "mvn package"
3. Navigate to the "target" folder
4. Inspect the contents of the JAR

As we can see, maven compiled the source file
into bytecode.




Maven follows a certain directory layout, thereby adhering to 
the "convention over configuration" principle.
More info here:
https://maven.apache.org/guides/introduction/introduction-to-the-standard-directory-layout.html



