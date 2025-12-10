# Group Policy and Cache Reset

## Commands

gpupdate /force

## Windows Update Reset

net stop wuauserv  
net stop bits  
net stop cryptsvc  
ren C:\Windows\SoftwareDistribution SoftwareDistribution.old  
ren C:\Windows\System32\catroot2 catroot2.old  
net start wuauserv  
net start bits  
net start cryptsvc  

## Notes
Clears cached policy and Windows Update corruption issues.
