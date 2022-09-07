#  cptcity_ferret
cptcity_ferret  is a collection of more than 12000 colour palettes for FERRET (https://ferret.pmel.noaa.gov/Ferret/).  
All these ferret-readable colour palettes (.spk) are prepared using the colour maps provided on the cpt-city (http://soliton.vm.bytemark.co.uk/pub/cpt-city/) website and use the same colour palette name. 

Files : spk_files.tar.xz (tar file of .spk files)

## Instruction  

Download the tar file and extract it into your local system.  Use the .spk files with paths for plotting. 


All these files can be easily accessed as inbuilt palettes if the spk files are copied into the "ppl" directory in the ferret source code. Make sure that copying these files will not replaces the existing .spk files in the “ppl” directory. A better option is to add a new PPL directory (export FER_PALETTE=) in ferret_paths file.


## Usage 


!       Example 1:- \
!Plot spatial map of SST using colour palette "temp_19lev.spk" in http://soliton.vm.bytemark.co.uk/pub/cpt-city/views/totp-cpt.html 


use coads_climatology \
fill/l=1/palette="/path/temperature.spk" sst  


!           Example 2:-\
! To use the reverse colour palette, use the suffix "_r.spk"  to the filename 

use coads_climatology \
fill/l=1/pal="/path/temperature_r.spk" sst 

## Add into the ferret source directory 
! if the spk files are copied into the "ppl" directory in the ferret source code, we can use these colours as regular in-built palettes without specifying the path and extension 

!           Example 3:- \
use coads_climatology \
fill/l=1/palette=temperature sst  

## Support 
I did not check all the cpt files individually. So please let me know if you find any problem with the colour palettes.
