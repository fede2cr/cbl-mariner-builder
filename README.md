# cbl-mariner-builder
Ansible recipes for auto building cbl-mariner

## Intro

Before porting to RISCV, we need an automated build environment (on x86-64) so that we can start changing the distro gradually.

## Objectives

- To compile cbl-mariner for a riscv64 target. Packages that don't compile will be reported as issues on this github repo.
- Modify the distro to create a bootable format compatible with any of the riscv64 boards available. Test with real hardware, and probably qemu and renode.

## Progress

- [x] Automate [pre-reqs](https://github.com/microsoft/CBL-Mariner/blob/1.0/toolkit/docs/building/prerequisites.md) with ansible
- [ ] Automate the building process using ansible
- [ ] Change target to riscv64 and start compiling tools and packages
- [ ] Create a bootable system, compatible with riscv64 boards, qemu or renode

## Testing hardware
- Sifive's Unleashed
- Beagleboard's BeagleV beta
- RVBoard's Nezha

