# bazel-lombok-generated-annotation

Bazel
=====
Install bazel - https://docs.bazel.build/versions/main/install.html

Run build with bazel
```
bazel build //example:problem
```

Buck
====

Download buck binary
```
curl https://jitpack.io/com/github/facebook/buck/0e72e40074e1731dd3c9068e5ed23ee10bcc75dd/buck-0e72e40074e1731dd3c9068e5ed23ee10bcc75dd.pex > buck.exe
chmod +x buck.exe
```

Run build with buck
```
./buck.exe build //example:problem
```

Differences
===========
Bazel output - output-jars/bazel-jar.jar

Buck output - output-jars/buck-jar.jar

Examine bytecode using luyten decompiler
```
java -jar luyten-0.5.4.jar
```

Bazel iJar class
![Bazel Generated Class](bazel_generated_annotation.png?raw=true "Bazel Class")

Buck iJar class
![Buck Generated Class](buck_generated_annotation.png?raw=true "Buck iJar Class")
