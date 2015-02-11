PUTTY_HOME, pointing to the location where all PuTTY binaries are stored
GIT_HOME, pointing to the location where git is installed
GIT_SSH with the value %PUTTY_HOME%\plink.exe
Add %PUTTY_HOME% and %GIT_HOME%\bin to Path environment variable, associated to your windows account. As an example, 
your Path variable could be set to something like this %Path%;%JAVA_HOME%\bin;%PUTTY_HOME%;%GIT_HOME%\bin;%MAVEN_HOME%\bin;%ANT_HOME%\bin
