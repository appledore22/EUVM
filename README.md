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


