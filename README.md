# Fast-slow
#
This package provides an implementation of the fast-slow explicit solvent model of molecular dynamics (MD) simulation.


Requirements


   gcc (Recommended version: >= 5.4.0) to compile file.
   
   AMBER (Recommended version: AMBER18) to generate the force field parameters files.
   

1. Install

(1). Extract the files in some location (we use /home/myname as an example here)

  cd /home/myname
  
  tar -xjf fast-slow.tar.bz2
  

(2). Compile file

  cd /home/myname/fast-slow
  
  make
  
The /home/myname//fast-slow/bin folder appears and contains the "md, md.OMP, and water_box" three files, indicating that the compilation is successful.


(3). Set environment variables

  adding the line
  
  export PATH=$PATH:/home/myname/fast-slow/bin
  
  to your startup file (e.g., ~/.bashrc).
  
