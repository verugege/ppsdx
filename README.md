
example:
conda activate ppsdx; ~/obspy-ppsd/./obspy-ppsd add -i ~/IA_TOLI2.seed ~/seiscomp/var/lib/archive/2024/IA/TOLI2/SHZ.D/IA.TOLI2..SHZ.D.2024.*;~/obspy-ppsd/obspy-ppsd plot ppsd_data_IA.TOLI2..SHZ.npz; conda deactivate

command :
```
$ conda activate ppsdx
$ obspy-ppsd -h
$ obspy-ppsd add -i inventory.xml folder_with_data/*.mseed
$ obspy-ppsd add -i inventory.xml folder_with_more_data/*.mseed
$ obspy-ppsd plot *.npz
$ obspy-ppsd timeplot 1,5,10 *.npz
$ obspy-ppsd spectrogram *.npz
$ shotwell ppsd_*.png
$ conda deactivate
```
