## Install Intel MKL

Follow the steps below to download and install intel mkl

```bash
# download the installer
wget https://registrationcenter-download.intel.com/akdlm/IRC_NAS/2ad98b49-1fb2-4294-ab3d-6889b434ebd3/intel-onemkl-2025.3.0.462_offline.sh

# run the installer, follow on screen instructions 
sh ./intel-onemkl-2025.3.0.462_offline.sh

# when you install, you should see where intel mkl is installed
# use this path to initialize 
source /home/min/a/$USER/intel/oneapi/setvars.sh
```