## The following steps were taken to create this repository

```
curl -LO http://www.coin-or.org/download/source/Ipopt/Ipopt-3.12.4.tgz
tar -xzf Ipopt-3.12.4.tgz
cd Ipopt-3.12.4
cd ThirdParty/
cd ASL/
./get.ASL
cd ../Blas/
./get.Blas
cd ../Lapack/
./get.Lapack
cd ../Metis/
./get.Metis
cd ../Mumps/
./get.Mumps
```
