# Multi-thread-Java-Server-for-Matlab
It is the java server that can be imported to Matlab. The socket provided by this java class is different from the Matlab's original socket support because it can support multiple socket being connected

# Usage
1. Build the java class. You can choose to use the ./build script or other IDE (like Eclipse) to build.
Note the version of your jdk should be set consistent to your Matlab's jvm version.

2. Add the bin path to your "static" java class of Matlab (dynamic path would not work). You can use the AddJavaClassPath.m script to finish this one-time setting.

3. Once you have added the server to your class path. Try to execute the TestClient.m script and see how multiple clients can talk to a Matlab socket simultaneously :)

