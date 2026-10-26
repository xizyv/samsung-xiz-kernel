# samsung-xiz-kernel

Custom kernel with ROOT for Samsung Galaxy A32 4G (SM-A325F, MT6768)

## Usage

Actions -> xizyv Kernel Factory -> Run workflow

| Input | Default | Meaning |
| --- | --- | --- |
| KREPO | samsung-mt6768-aosp | kernel source |
| KBRANCH | lineage-24.0 | kernel branch |
| DCFG | mt6768-unifiedk414_lineage_defconfig | base defconfig |
| FRAG | a32.config | device fragment merged into base |
| REBRAND | xizyv-a32 | CONFIG_LOCALVERSION |
| KSU | baka | root solution or non-root |
| ZREPO | MrGadget84/AnyKernel3 | packer |
| ZBRANCH | a325f | packer branch |

## Credits

- Kernel: samsung-mt6768-aosp/android_kernel_samsung_mt6768
- Root: BakaSU
- Packer: AnyKernel3
