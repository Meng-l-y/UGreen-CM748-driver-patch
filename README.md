# UGreen-CM748-driver-patch
bluetooth dongle: UGreen CM748 bt5.4
chip: Barrot BR86540A02

the patch file is for kernel version 6.12.47.

1. setup before init.
2. one extra byte in read_ext_features, disable read_ext_features or fix it (drop the extra byte).

the dongle functions after patch. still some minor issues.
