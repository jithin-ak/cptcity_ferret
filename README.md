# cptcity_ferret
This contains more than 12000 color palette for FERRET (https://ferret.pmel.noaa.gov/Ferret/) 
All these files are taken from  cpt-city (http://soliton.vm.bytemark.co.uk/pub/cpt-city/) website and uses the same colour palete name. 

Files : spk_files.tar.xz (tar file of .spk files)

# Instruction  

Download the tar file and extract it into your local system.  Use the files with path for plotting. 


All these files can be easily accessed as in built palettes if the spk files are copied into "ppl" directory in the ferret source code. Make sure that copying  these files will not replaces your original .spk files in the ppl directory.


# Usage 

plot spatial map of SST using colour palatte "temp_19lev.spk" in http://soliton.vm.bytemark.co.uk/pub/cpt-city/views/totp-cpt.html

use coads_climatology \
fill/l=1/palette=/path/temp_19lev.spk sst  

! To use the reverse colour palatte, use the suffix "_r.spk"  to the flename \

fill/l=1/pal=/path/balance_r.spk sst 

! if the spk files are copied into "ppl" directory in the ferret source code. 

use coads_climatolgy \
fill/l=1/palette=temp_19lev sst  





