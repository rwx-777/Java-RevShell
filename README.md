# Java-RevShell
Java rev shell tested on Android 8


# compile Java source code
javac ReverseShell.java

# convert to DEX format 
/path/to/your/android/sdk/build-tools/28.0.3/dx --dex --output classes.dex ReverseShell.class

# create fake JAR file
zip ars.jar classes.dex

