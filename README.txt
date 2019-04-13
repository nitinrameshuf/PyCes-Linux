PyCes Runbook 

Introduction 

The PyCes - [Python Code Scanner] - helps the assessor by 

1) Automating most of tasks/scans which are to be run on the python code.

2) Introduces new rules which help to run a more comprehensive scan on the code.

3) Runs the following tools on the code: Cloc, Bandit, 3rd party lib detector, Pymcd and Dependency Check. 


***

Prerequisites

The PyCes tool is almost self-contained to run most tests required on the code. 

But few requirements are:

System needs Python 3 installed.

The bandit tool if not present can be installed on the host machine.

It can be installed in Linux by the following command:

pip install bandit

Note: If PIP is not set in the system,it can be found at the location python is installed in the system. (\Python27\Scripts\pip.exe)

***

Running the PyCes

Step 1: Copy and extract the zipped folder to any location in the machine.(Make sure the path where the folder is placed has no spaces or special character expect underscore in them such as "C:\example\space folder".This is recommended "C:\example\space_folder")

Step 2: Place the code in the >Test_Project folder inside the PyCes folder. Remove any previous code or projects if present inside this folder.

Step 3:  Doubkle click the runner.bat file.


***

Note:
In case the test fails,individual reports of successfully run tests will be placed in the same folder.
