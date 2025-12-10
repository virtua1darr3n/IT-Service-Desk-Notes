# DISM – Windows Image Repair

## Purpose
Repairs the Windows operating system image when corruption is detected.

## Main Command

DISM /Online /Cleanup-Image /RestoreHealth

## Additional Commands

DISM /Online /Cleanup-Image /ScanHealth  
DISM /Online /Cleanup-Image /CheckHealth  

## When to Use
Run if SFC cannot repair system files or Windows Update fails.
