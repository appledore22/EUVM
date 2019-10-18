# EUVM
### Adding EUVM 
wget http:/download.uvm.io/euvm-1.0-beta4.tar.xz  
tar euvm-1.0-beta4.tar.xz  
tar xf euvm-1.0-beta4.tar.xz  
cd euvm-1.0-beta4/bin  
export PATH=~/euvm-1.0-beta4/bin:$PATH  

mkdir work  
cd work  
git clone https://github.com/uvm/avst_adder.git  
cd avst_adder/testbench  
make  
make run  

### Websites
chipsalliance.org  
agilemanifesto.org  

### Books
Gang of Four : Uncle Bob  
Writing Testbench using SV : Janick Bergeron  
A Practical Guide to Adopting the Universal Verification Methodology (UVM) Second Edition : Sharon Rosenberg and Kathleen Meade  
Hardware Design Verification : William Lam  
The UNIX Programming Environment Paperback – 2015 by Kernighan & Pike   

### Repositires
Files from the wrokshop were downloaded from -  
https://github.com/uvm

### Git Commands
git reset --hard  
Removes the changes made after recent commit

git logs  
show the history of commit  

git add  
Adds files to stage for commiting  

git status  
Shows the status(untracked,tracked,staging) for different files

git push
Pushs the changes from local repo to remote repo  

### Commands for ssh
ssh-keygen  
Generating new ssh key file.  




