Installation Requirements:
--------------------------
1.	ScalaIDE for Eclipse is needed

	* Download from http://scala-ide.org/download/sdk.html
	* For Projects imported into Eclipse set the Scala version to 2.10.6 under Project/Properties/Scala Compiler
2. Maven
	* https://maven.apache.org/install.html

3. Git (Nice to have)
	* https://git-scm.com/book/en/v2/Getting-Started-Installing-Git
4. Tutorial code & data
	* Download or ```git clone``` the from https://github.com/jayantshekhar/strata-2016 (You are here!!)
5. Build with 'mvn package'
6. Import into ScalaIDE for Eclipse as a maven project
7. Ensure to set the Scala version for the project in the IDE to be 2.10.6. Without it, you would run into compiler issues.


If you don't have a local Hadoop installation, you have to set the variable HADOOP_CONF
Otherwise you will get an error "... Exception: Could not locate executable null\bin\winutils.exe in the Hadoop ..."

For Windows Users
-----------------

If you don't have a local Hadoop installation, you have to set the variable HADOOP_CONF
Otherwise you will get an error "... Exception: Could not locate executable null\bin\winutils.exe in the Hadoop ..."
 
Download http://public-repo-1.hortonworks.com/hdp-win-alpha/winutils.exe and put it to DISK:\FOLDERS\bin\

Set the variable 
HADOOP_CONF=DISK:\FOLDERS


