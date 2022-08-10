# f1search
Attempts to locate f1(1285) meson (PDG ID# 20223) through various decay methods.

Simulations (CLAS12 Monte Carlo) used/created from:
https://gemc.jlab.org/web_interface/index.php 
JLab account required.

Local coatjava 8.0.0 installation required:
https://github.com/JeffersonLab/clas12-offline-software/releases
Unpack file with command: tar -xzvf coatjava-8.0.0.tar.gz

Java 11 required to run jshell.
To load in multiple .jar files with jshell, call:
jshell --class-path ~/coatjava/lib/clas/coat-libs-8.0.0-SNAPSHOT.jar:~/coatjava/lib/clas/JEventViewer-1.1.jar:~/coatjava/lib/clas/vecmath-1.3.1-2.jar
