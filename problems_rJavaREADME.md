#Trying to install rJava and having problems with the load of library(rJava)

#the message: "erro: JAVA_HOME cannot be determined from the Registry"

#the message: "erro: impossível carregar objeto compartilhamento 'C:/Users/Katharine/Documents/R/win-library/4.0/rJava/libs/x64/rJava.dll':"

#it'necessary to already have the Java Run Time and the JDK installed

#now it's only to follow these steps below: 

> **install.packages("rJava")**

# this message will show up: 

<package ‘rJava’ successfully unpacked and MD5 sums checked

The downloaded binary packages are in
        C:\Users\Katharine\AppData\Local\Temp\RtmpKQJByy\downloaded_packages>
 
#for windows 10: search for Environment Variables and select Edit the system environment variables -> Environment Variables -> Under System Variables and click 'New' -> Variable Name: JAVA_HOME and Variable Value: C:\Program Files\Java\jre1.8.0_251

#now it's only fallow the steps below:

> **Sys.setenv(JAVA_HOME="C:/Program Files/Java/jdk-14.0.1")**

> **library(rJava)**
