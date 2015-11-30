#high mass version of vhbb code

cmsrel CMSSW_7_4_15

cd CMSSW_7_4_15/src

cmsenv

git clone -b add_regAK08 https://github.com/degrutto/highmassvhbb.git

cd VHbbAnalysis/Heppy/test

python vhbb_combined.py
