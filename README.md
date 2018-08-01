# work-diary.   
Mon, 30 July 2018.   
creat github page for WDL.   
download WDLTool and  SublimeText.   
test WDLTool with command:     
$ cd /Users/shuanglu/Documents/cromwell    
$ java -jar wdltool-0.14.jar.   
The installation of Cromwell itself is quite simple. The latest release can be downloaded [here](https://github.com/broadinstitute/cromwell/releases) in the form of a pre-compiled jar.     
For ease of use, you can also [add an environment variable to your terminal profile](https://www.cyberciti.biz/faq/set-environment-variable-linux/) pointing at the Cromwell jar file.   

Task: Set Environment Variables on Linux

You can modify each environmental or system variable using the export command. Set the PATH environment variable to include the directory where you installed the bin directory with perl and shell scripts:

export PATH=${PATH}:/home/vivek/bin
OR

export PATH=${PATH}:${HOME}/bin
To set the JAVA_HOME environment variable to the directory where you installed the J2SE SDK application, enter:

export PATH=${PATH}:/usr/java/jdk1.5.0_07/bin
You can set multiple paths as follows:

export ANT_HOME=/path/to/ant/dir
export PATH=${PATH}:${ANT_HOME}/bin:${JAVA_HOME}/bin


Java 8
Cromwell requires Java version 8, which you can find [here](https://software.broadinstitute.org/wdl/documentation/quickstart).    
Docker (optional). 
