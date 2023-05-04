# how-to-generate-sha-1-and-sha-256-from-vscode-for-flutter-app


On the vscode terminal, enter cd android
then run   .\gradlew signingReport

NB: if you are getting build fail error, add this to your environment for windows:
Variable name: JAVA_HOME
Variable value : C:\Program Files\Android\Android Studio\jre
You need to have android studio on your PC to work.
Then restart your terminal to effect the changes.



USE: ./gradlew signingReport
For Macbook


https://stackoverflow.com/questions/64359564/error-java-home-is-not-set-and-no-java-command-could-be-found-in-your-flutter/64374658
