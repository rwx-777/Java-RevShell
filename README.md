# Java-RevShell
Java rev shell tested on Android 8


# compile Java source code
javac ReverseShell.java

# convert to DEX format 
/path/to/your/android/sdk/build-tools/28.0.3/dx --dex --output classes.dex ReverseShell.class

# create fake JAR file
zip ars.jar classes.dex



Awesome Work:
https://malacupa.com/2018/10/25/android-command-line-reverse-shell.html

