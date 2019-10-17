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

### Repositires
Files from the wrokshop were downloaded from -  
https://github.com/uvm



