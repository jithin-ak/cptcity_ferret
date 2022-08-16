# cptcity_ferret
This contains ferret readable format of all the colour palettes given in  cptcity (http://soliton.vm.bytemark.co.uk/pub/cpt-city/) website. 
All the files (more than 6000 palattes and its reverse order) in the website are coverted into ferret readable format. 

Files : spk_files.tar.xz (tar file of .spk files)

# Usage  

Download the tar file and extract it into your local system. And use the files with path for plotting. 

All these files can be easily accessed as in built palettes if the spk files are copied into "ppl" directory in the ferret source code. 


! Example 1 \
use coads_climatology \
fill/l=1/palette=/path/temp_19lev.spk sst  

! Example 2\
! For the reverse colour palatte, use "name_r.spk" \
fill/l=1/pal=/path/balance_r.spk sst 

! if the spk files are copied into "ppl" directory in the ferret source code. 

! Examples 3 
use coads_climatolgy \
fill/l=1/palette=temp_19lev sst  





