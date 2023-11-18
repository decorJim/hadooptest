Test Hadoop map reduce code without setting up hadoop on a remote machine

- open intellij IDEA
- create a maven project
- install the necessary dependency in pom.xml
- go to "edit configuration"
- give it a name "could be the project name"
- choose your java version (java 20 Amazon Corretto version 20.0.2 for this project)
- if not downloaded on your machine, you can use intellij to download it directly
- Choose the main class as "Main.java"
- in hadooptest directory create the folder "input" and put a file with .txt extension containing your dataset inside
- if the project create is located in "Desktop"
- set CLI arguments as "/Users/username/Desktop/hadooptest/input /Users/username/Desktop/hadooptest/output"