## R CMD check results

rgrass 0.5-3 ────

Update to allow rgrass to gracefully fail (without raisingwarnings or errors) 
and skip tests when the internet resources required to download the GRASS 
example database are unavailable.

Caused by error in `download.file()`:
! download from 'https://grass.osgeo.org/sampledata/north_carolina/nc_basic_spm_grass7.zip' failed
