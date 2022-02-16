## HMMER - biological sequence analysis using profile HMMs

This is a copy of the arm branch of hmmer software. Since it's not released yet, I will just put everything needed here for users that want to use it natively on ARM64 machines.

The orginal repo is here: https://github.com/EddyRivasLab/hmmer

```
### download h3-heno branch of hmmer here (do not git clone but download zip):

https://github.com/EddyRivasLab/hmmer/tree/h3-arm

## go into the donwloaded directory and download Easel develop branch here (do not git clone but download zip) :
cd h3-arm
https://github.com/EddyRivasLab/easel/tree/develop

## compile
autoconf
./configure
make -j 8
sudo make install
hmmsearch -h
```

Note: I do not have a ARM linux at hand, feel free to also upload ARM Linux binaries for the community.

