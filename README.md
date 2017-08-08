# How to Configure selenium programme through jenkins
### Prerequisites 
*   [Selenium jar files](http://docs.seleniumhq.org/download/) 
*   [Selinium standalone server jar](http://docs.seleniumhq.org/download/) 
*   [Testng jar files](http://testng.org/doc/download.html) 
<p>* Create a one java programme in eclipse</p>
<p>* convert java programe in to testng.xml</p>

### How to convert java programe in to testng.xml  
  <p>Right click on your project.
  <p>Move to Testng tab.click on convert into testng file.
  <p>click on ok button.
<p>Automatically testng file is created in your project folder.</p>


### Set up your folder 
<p> Go to your project folder location
<p>create one new folder rename as lib
<p>In lib folder save the all libraries  files like
<p>* selenium jar files
<p>* selenium standalone server jars
<p>* testng files
<p>* poi files</p>


### Set up your batch file
Open notepad file write here like this:
<p>*These five lines of code should mandatory

<p>1.set projectlocation=Give her project location folder
<p>2.set classpath=%projectlocation%\bin;%projectlocation%\Give here your new created lib folder name\*
<p>3.set projectlocationwithxml="C:\Users\COMPAQ\workspace\Selenium First\testng.xml"
<p>4java org.testng.TestNG %projectlocationwithxml%
<p>5.pause

<p>Save it has "name.Bat"(Here double qutations is required)

<p> Now to run this file in command prompt 

### How to run batch file command prompt 
<p> Double click on batch file






