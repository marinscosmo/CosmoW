# CosmoW
# 
This set code was make by Alessandro Marins (University of Sao Paulo).
For any questions, please, contact me in alessandro.marins@usp.br.


This is a set of cosmological codes in python for calculate 21cm angular power spectrum and Baryon Acoustic Oscillations analysis.

You can use it for building Cl21cm and Cl21cm_smoothed, both are make with Eisenteins&Hu Transfer Functions. This code was make for BINGO Radiotelescope characteristics.

For run a example of the code open the terminal in the CosmoW directory and writing

python Building_Cl.py --nbin 30 --lmin 1 --lmax 200

for 30 numbers bins (number channels) and maximum and minimun multipole l.
It will generate ".txt" files in cl directory.

For BAO analisys, use Building_Clbao.py. This will generate files in clbao directory.
