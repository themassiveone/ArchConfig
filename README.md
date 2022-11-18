# ArchConfig

## fdisk
Doing the fdisk configuration can be simplified using config dumps. Choose the correct one depending on disk size and function.

## Formatting
Partitions need to be formatted.
Use either of those for your partitions:
- mkfs.ext4: os
- mkswap: swap
- mkfs.fat -F 32: efi
