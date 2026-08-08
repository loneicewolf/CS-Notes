# kvm on this laptop with debian
```
Ram:       16GB RAM
Storage: 500GB  SSD (M.2,NVMe,PCI.e 4.0)
CPU:         Ryzen7  7730U [ 2 threads per socket, 8 cores per socket, 1 socket ] 
ssd_1 {debian}
```

- sudo apt install (....) qemu-system  (...)
  -   qemu-system for `sudo kvm-ok` [x] check

# note  this was a old laptop which now is broken.. now i have this:

```
Architecture:                x86_64
  CPU op-mode(s):            32-bit, 64-bit
  Address sizes:             46 bits physical, 48 bits virtual
  Byte Order:                Little Endian
CPU(s):                      14
  On-line CPU(s) list:       0-13
Vendor ID:                   GenuineIntel
  Model name:                Intel(R) Core(TM) Ultra 5 125U
    CPU family:              6
    Model:                   170
    Thread(s) per core:      2
    Core(s) per socket:      12
    Socket(s):               1
    Stepping:                4
    CPU(s) scaling MHz:      33%
    CPU max MHz:             4300.0000
    CPU min MHz:             400.0000
Virtualization features:     
  Virtualization:            VT-x
Caches (sum of all):         
  L1d:                       352 KiB (10 instances)
  L1i:                       640 KiB (10 instances)
  L2:                        10 MiB (5 instances)
  L3:                        12 MiB (1 instance)
NUMA:                        
  NUMA node(s):              1
  NUMA node0 CPU(s):         0-13
```
