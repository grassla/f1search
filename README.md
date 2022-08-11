# f1search
***Display the Source Blob (<>) for nicer viewing***
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



Contents:
Note that some files are not intended for pion pairs.
Note all files banks - Most are REC::Particle or MC::Lund.

pions_match                  searches for events with 2 + and 2 - pions
pions_inv_mass               shows H1F histogram of invariant mass of 2 + and 2 - pions
split_inv_mass               shows H1F histograms of + pion and - pion pairs (+0 with -0, +1 with -0, etc.)
split_inv_mass_H2F           shows H2F histograms of + pion and - pion pairs
type                         shows type (i.e. if final decay state) of pions
q2_and_w                     shows H1F histograms of Q2 and W of events
q2_w_t_p                     shows H1F histograms of Q2, W, theta, and phi and H2F histogram of theta v phi of events
q2_v_w                       shows H2F histogram of Q2 v W
parents                      shows parent (index!) of final decay state particles
pions_parents                shows parent pid of + pions and - pions
pion_parents_pid             counter of diffferent pion (not pairs) parents
pion_parents_histo           histogram of pion (not pairs) parents
pion_pairs_parents           counter of different paired pion parents pids and histogram
pion_parents_inv_mass        H1F histogram of paired pion parents invariant mass
pairs_parents_generational   shows where paired pions parents (i.e. eta, omega, rho, K0short) came from with H1F histograms
pairs_parents_inv_mass shows H1F histograms of paired pion parents' parents invariant masses
