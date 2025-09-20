# RISC-V Reference SoC Tapeout Program VSD
## Tools Installation
### All the instructions for installation of required tools can be found here:
System Requirements
- 6 GB RAM
- 50 GB HDD
- Ubuntu 20.04 or higher
- 4 vCPU
## Tool Check
### 1. Yosys
```bash
$ sudo apt-get update
$ git clone https://github.com/YosysHQ/yosys.git
$ cd yosys
$ sudo apt install make   
$ sudo apt-get install build-essential clang bison flex \
    libreadline-dev gawk tcl-dev libffi-dev git \
    graphviz xdot pkg-config python3 libboost-system-dev \
    libboost-python-dev libboost-filesystem-dev zlib1g-dev
$ make config-gcc
$ make
$ sudo make install
```
## Install verification:
 ![WhatsApp Image 2025-09-20 at 18 40 14_d11fd199](https://github.com/user-attachments/assets/efe66333-3e81-473f-9c43-b912868d80d8)

### 2. Iverilog
```bash
$ sudo apt-get update
$ sudo apt-get install iverilog
```
## Install verification:
![WhatsApp Image 2025-09-20 at 18 42 15_74146529](https://github.com/user-attachments/assets/f74e2d94-8e4a-413a-94db-a2ce3ca50914)

### 3. gtkwave
   ```bash
   $ sudo apt-get update  
   $ sudo apt install gtkwave 
   ```
   ## Install verification:
   ![WhatsApp Image 2025-09-20 at 18 43 09_8e8e369e](https://github.com/user-attachments/assets/74d59bc7-368e-46ff-aef1-9da53178ba09)
