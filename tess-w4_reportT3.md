Frequency analysis on First Light TESS roAp stars 
================
Granada PLATO Team
10/24/2018


## Abstract

This report contains the `FFT` (of the ARMA gap-filled TESS light curve) and 
powerspectra (from `SigSpec`).
For each star the comparison of both diagrams are displayed in a figure with 
two panels.

## The G3 data

The list of **G3** stars are provided in the <https://tasoc.dk/wg4/> website. 
The light curves were downloaded from MAST repository.


```{r g3 data}
pathdata <- "/Users/jcsuarez/Data/obs/TESS/Grupo3/"
filename <- paste(pathdata,"g3_tessFLstars.csv", sep = "")
data <- read.csv(file = filename, header = T, sep = ",", 
                             stringsAsFactors = FALSE)
```

![](FiguresG3/g3data_ini.png)


## G3 output results

This table summarizes the results found for all the objects for which both FFT and SigSpec
data were available (two stars dropped out)

![](FiguresG3/g3_results.png)

## FFT and PWT plots 

This section contains all the figures on which we based the results given in table above.

### 182909257

![](FiguresG3/182909257.dat.png)

**Coments:** MIARMA LC ok(*), Prot 1/0.31 (sale doble), freq SigSpec 

### 183802606_s1

![](FiguresG3/183802606_s1.dat.png)

**Coments:** MIARMA LC ok(*), Prot 1/0.44 (sale doble), freq SigSpec 

### 183802904

![](FiguresG3/183802904.dat.png)

**Coments:** MIARMA LC ok, Prot 1/0.04 (no sale doble ya que nu_rot cercano a 0), freq SigSpec

### 234346165_s1

![](FiguresG3/234346165_s1.dat.png)

**Coments:** MIARMA LC Bad, Prot 1/0.31 (sale doble), freq SigSpec (WARNING por relleno)

### 234346165_s2

![](FiguresG3/234346165_s2.dat.png)

**Coments:** MIARMA LC Ok(*), Prot 1/0.31 (sale doble), freq SigSpec


### 24693528

![](FiguresG3/24693528.dat.png)

**Coments:** MIARMA LC OK(*), No Prot, freq SigSpec (Clasific DScuti)

### 262956098

![](FiguresG3/262956098.dat.png)

**Coments:** MIARMA LC Ok(*), Prot 1/0.22 (sale doble), freq SigSpec


### 266905315

![](FiguresG3/266905315.dat.png)

**Coments:** NO VALIDAMOS


### 271503787_s1

![](FiguresG3/271503787_s1.dat.png)

**Coments:** MIARMA LC Ok(*), Prot 1/0.2 (sale doble aprox), freq SigSpec


### 280051011

![](FiguresG3/280051011.dat.png)

**Coments:** NO VALIDAMOS

### 304096024_s1

![](FiguresG3/304096024_s1.dat.png)

**Coments:** MIARMA LC Ok, Prot 1/0.13 (sale doble), freq SigSpec

### 31870361

![](FiguresG3/31870361.dat.png)

**Coments:** MIARMA LC OK(*), No Prot, freq SigSpec (Clasific DScuti)

### 392761412

![](FiguresG3/392761412.dat.png)

**Coments:** MIARMA LC Ok(*), Prot 1/0.48 (sale doble), freq SigSpec

### 52368859

![](FiguresG3/52368859.dat.png)

**Coments:** MIARMA LC Ok(*), Prot 1/0.62 (sale doble), freq SigSpec








