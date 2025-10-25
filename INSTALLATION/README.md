# OpenROAD Quick Installation Guide

```bash
# 1. Clone repository
git clone --recursive https://github.com/The-OpenROAD-Project
cd OpenROAD


# 2. Install dependencies
sudo ./etc/DependencyInstaller.sh -all
```

```
# 3. Build OpenROAD
mkdir build
cd build
cmake ..
make
```
![OpenROAD Installation Diagram](https://github.com/Sam25-GitHub/RISC-V-SoC-TAPEOUT_OPENROAD/blob/main/INSTALLATION/2_openroad.jpg?raw=true)
![OpenROAD Installation Diagram](https://github.com/Sam25-GitHub/RISC-V-SoC-TAPEOUT_OPENROAD/blob/main/INSTALLATION/3_openroad.jpg?raw=true)

```
# 4. Run OpenROAD
cd test/
openroad -gui -log filename.log verilog_descriptive.tcl
```
![OpenROAD Installation Diagram](https://github.com/Sam25-GitHub/RISC-V-SoC-TAPEOUT_OPENROAD/blob/main/INSTALLATION/4-openroad.jpg?raw=true)
![OpenROAD Installation Diagram](https://github.com/Sam25-GitHub/RISC-V-SoC-TAPEOUT_OPENROAD/blob/main/INSTALLATION/5_openroad.jpg?raw=true)
