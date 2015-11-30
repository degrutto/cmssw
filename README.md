#high mass version of vhbb code
cmsrel CMSSW_7_4_15
cd CMSSW_7_4_15/src
cmsenv
git cms-merge-topic degrutto:highmassvhbb
cd VHbbAnalysis/Heppy/test
python vhbb_combined.py
