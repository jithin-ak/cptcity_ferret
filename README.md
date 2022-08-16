# cptcity_ferret
This contains ferret readable format of all the colour palettes given in
cptcity (http://soliton.vm.bytemark.co.uk/pub/cpt-city/) website. 

# Instructions : 
Color palate Name : Same name as in http://soliton.vm.bytemark.co.uk/pub/cpt-city/ .
All the files (more than 6000 palattes and its reverse) in the website are coverted into ferret readable format. 

# Examples 
use coads_climatology
fill/l=1/palette=/path/temp_19lev.spk sst  

# For the reverse colour palatte, use "name_r.spk" 
fill/l=1/pal=/path/balance_r.spk sst 

# All these files can be easily accessed as in built palettes if the spk files are 
copied into "ppl" directory in the ferret source code
# Examples 
use coads_climatolgy
fill/l=1/palette=temp_19lev sst  





