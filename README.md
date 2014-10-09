HIPAlignment
============

To obtain and run the code, do the following:

setenv SCRAM_ARCH slc5_amd64_gcc482
cmsrel CMSSW_7_0_5
cd CMSSW_7_0_5/src
git clone git@github.com:aspiezia/HIPAlignment
mv HIPAlignment/Alignment/ .
mv HIPAlignment/Configuration/ .
scram b
