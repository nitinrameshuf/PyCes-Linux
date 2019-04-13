PyCes ReadMe 

Introduction 
PyCes (Python Code Scanner) is an automated enhanced capability security static analysis tool for Python.

PyCes gives a consolidated HTML report with the following:
> Type and line content of various types of code in the package.
> Any public third-party libraries that may be present in the code.
> List of potential Python vulnerabilities present in code.
> Dependency check report by OWASP DC.
> Grep based search for any vulnerable patterns which may be present in the code.

Its magic comes is partly due to the greatly enchanced ruleset which covers security vulnerabilties for multiple Python frameworks in the market.

***

Prerequisites

The PyCes tool is almost self-contained to run most tests required on the code. 

But few requirements are:

System needs Python 3 installed.

The bandit tool if not present can be installed on the host machine.

It can be installed in Linux/Windows by the following command:

pip install bandit

Note: If PIP is not set in the system,it can be found at the location python is installed in the system. (\Python27\Scripts\pip.exe)

***

Running the PyCes

Step 1: Copy and extract the zipped folder to any location in the machine.(Make sure the path where the folder is placed has no spaces such as "C:\example\space folder".This is recommended "C:\example\space_folder")

Step 2: Place the code in the >Test_Project folder inside the PyCes folder. Remove any previous code or projects if present inside this folder.

Step 3:  Doubkle click the runner.bat file.


***

Note:
In case the test fails,individual reports of successfully run tests will be placed in the same folder.
