# Zygisk on KernelSU

Zygisk loader for KernelSU, allowing Zygisk modules to run without Magisk environment.

Also works as standalone loader for Magisk on purpose of getting rid of LD_PRELOAD.

## Requirements

+ Minimal KernelSU version: 10654
+ Minimal ksud version: 10647
+ Full SELinux patch support (If non-gki kernel)
+ No multiple root implementation installed

## Compatibility

Should work with everything except those rely on Magisk internal behaviors.
