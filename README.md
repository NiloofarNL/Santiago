
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Santiago

<!-- badges: start -->
<!-- badges: end -->

The goal of Santiago is to contribute to psychological impacts on
travelers by examining the feelings of stress by users of active and
motorized modes of transportation.Furthermore, it also investigates the
importance that travelers attach to their feelings of stress. More
words.

## Installation

You can install the development version of Santiago from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("NiloofarNL/Santiago")
#> Downloading GitHub repo NiloofarNL/Santiago@HEAD
#>          checking for file 'C:\Users\bahman.notebook\AppData\Local\Temp\Rtmp0GWXAK\remotes468c1ec64246\NiloofarNL-Santiago-1f98375/DESCRIPTION' ...  v  checking for file 'C:\Users\bahman.notebook\AppData\Local\Temp\Rtmp0GWXAK\remotes468c1ec64246\NiloofarNL-Santiago-1f98375/DESCRIPTION' (435ms)
#>       -  preparing 'Santiago': (492ms)
#>    checking DESCRIPTION meta-information ...     checking DESCRIPTION meta-information ...   v  checking DESCRIPTION meta-information
#>       -  checking for LF line-endings in source and make files and shell scripts
#>       -  checking for empty or unneeded directories
#>       -  building 'Santiago_0.0.0.9000.tar.gz'
#>      
#> 
#> Installing package into 'C:/Users/bahman.notebook/Documents/R/win-library/4.1'
#> (as 'lib' is unspecified)
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(Santiago)
data("SantiagoSurvey")
```

## basic example code

What is special about using `README.Rmd` instead of just `README.md`?
You can include R chunks like so:

``` r
summary(SantiagoSurvey)
#>      NUMERO         ORIGEN           r0A_COMUNA        r0B_MACRO ZONA    
#>  Min.   :  1.0   Length:451         Length:451         Length:451        
#>  1st Qu.:113.5   Class :character   Class :character   Class :character  
#>  Median :226.0   Mode  :character   Mode  :character   Mode  :character  
#>  Mean   :226.0                                                           
#>  3rd Qu.:338.5                                                           
#>  Max.   :451.0                                                           
#>                                                                          
#>  r0B_CALLE_1        r0B_CALLE_2         r0C_GENERO          r0D_EDAD        
#>  Length:451         Length:451         Length:451         Length:451        
#>  Class :character   Class :character   Class :character   Class :character  
#>  Mode  :character   Mode  :character   Mode  :character   Mode  :character  
#>                                                                             
#>                                                                             
#>                                                                             
#>                                                                             
#>     r0E_PESO        r0F_ALTURA    r0G_EDUCACION      r0H_OCUPACION     
#>  Min.   : 42.00   Min.   :146.0   Length:451         Length:451        
#>  1st Qu.: 60.00   1st Qu.:160.0   Class :character   Class :character  
#>  Median : 68.00   Median :167.0   Mode  :character   Mode  :character  
#>  Mean   : 69.60   Mean   :167.2                                        
#>  3rd Qu.: 79.75   3rd Qu.:174.0                                        
#>  Max.   :120.00   Max.   :197.0                                        
#>  NA's   :29       NA's   :20                                           
#>  r0I_COM_TRAB_1     r0I_COM_TRAB_2     r0J_INGRESO         r0K_ADULTOS   
#>  Length:451         Length:451         Length:451         Min.   :1.000  
#>  Class :character   Class :character   Class :character   1st Qu.:2.000  
#>  Mode  :character   Mode  :character   Mode  :character   Median :3.000  
#>                                                           Mean   :2.812  
#>                                                           3rd Qu.:4.000  
#>                                                           Max.   :7.000  
#>                                                           NA's   :5      
#>    r0L_NIÑOS      r0N_LICENCIA       r0M_DISCAPA          r0O_TIPO        
#>  Min.   :0.0000   Length:451         Length:451         Length:451        
#>  1st Qu.:0.0000   Class :character   Class :character   Class :character  
#>  Median :0.0000   Mode  :character   Mode  :character   Mode  :character  
#>  Mean   :0.6562                                                           
#>  3rd Qu.:1.0000                                                           
#>  Max.   :6.0000                                                           
#>  NA's   :6                                                                
#>   r0P_MODO1          r0Q_MODO2          r0R_MODO3           r1A_ESTRES  
#>  Length:451         Length:451         Length:451         Min.   :1.00  
#>  Class :character   Class :character   Class :character   1st Qu.:2.00  
#>  Mode  :character   Mode  :character   Mode  :character   Median :3.00  
#>                                                           Mean   :3.02  
#>                                                           3rd Qu.:4.00  
#>                                                           Max.   :5.00  
#>                                                           NA's   :2     
#>   r1B_ESFUERZO    r1C_CERCANIA     r1D_CONTAM      r1E_SEGUR      r1F_COMOD    
#>  Min.   :1.000   Min.   :1.000   Min.   :1.000   Min.   :1.00   Min.   :1.000  
#>  1st Qu.:3.000   1st Qu.:1.000   1st Qu.:1.000   1st Qu.:2.00   1st Qu.:2.000  
#>  Median :3.000   Median :2.000   Median :2.000   Median :3.00   Median :3.000  
#>  Mean   :3.249   Mean   :2.594   Mean   :2.188   Mean   :2.68   Mean   :2.667  
#>  3rd Qu.:4.000   3rd Qu.:4.000   3rd Qu.:3.000   3rd Qu.:4.00   3rd Qu.:4.000  
#>  Max.   :5.000   Max.   :5.000   Max.   :5.000   Max.   :5.00   Max.   :5.000  
#>  NA's   :2       NA's   :8       NA's   :4       NA's   :1      NA's   :1      
#>   r1GA_ESTRES     r1GB_ESFUER      r1GC_CERC      r1GD_CONTAM   
#>  Min.   :1.000   Min.   :1.000   Min.   :1.000   Min.   :1.000  
#>  1st Qu.:4.000   1st Qu.:3.000   1st Qu.:3.000   1st Qu.:4.000  
#>  Median :5.000   Median :4.000   Median :4.000   Median :5.000  
#>  Mean   :4.227   Mean   :3.731   Mean   :3.903   Mean   :4.224  
#>  3rd Qu.:5.000   3rd Qu.:5.000   3rd Qu.:5.000   3rd Qu.:5.000  
#>  Max.   :5.000   Max.   :5.000   Max.   :5.000   Max.   :5.000  
#>  NA's   :6       NA's   :5       NA's   :7       NA's   :4      
#>    r1GE_SEGUR      r1GF_COMOD    r2AA_LIBERTAD       r2AB_INSEG       
#>  Min.   :1.000   Min.   :1.000   Length:451         Length:451        
#>  1st Qu.:4.000   1st Qu.:3.000   Class :character   Class :character  
#>  Median :5.000   Median :4.000   Mode  :character   Mode  :character  
#>  Mean   :4.513   Mean   :4.126                                        
#>  3rd Qu.:5.000   3rd Qu.:5.000                                        
#>  Max.   :5.000   Max.   :5.000                                        
#>  NA's   :5       NA's   :5                                            
#>  r2AC_FUNCIONA      r2AD_ENTRET         r2AE_COSTO        r2AF_POBREZ       
#>  Length:451         Length:451         Length:451         Length:451        
#>  Class :character   Class :character   Class :character   Class :character  
#>  Mode  :character   Mode  :character   Mode  :character   Mode  :character  
#>                                                                             
#>                                                                             
#>                                                                             
#>                                                                             
#>  r2AG_SEGURIDAD     r2AH_TIEMPO        r2AI_IMPUNT        r2AJ_CONGEST      
#>  Length:451         Length:451         Length:451         Length:451        
#>  Class :character   Class :character   Class :character   Class :character  
#>  Mode  :character   Mode  :character   Mode  :character   Mode  :character  
#>                                                                             
#>                                                                             
#>                                                                             
#>                                                                             
#>  r2AK_EFICIENC       r2AL_LUJO         r2AM_AMBIENT        r2AN_SALUD       
#>  Length:451         Length:451         Length:451         Length:451        
#>  Class :character   Class :character   Class :character   Class :character  
#>  Mode  :character   Mode  :character   Mode  :character   Mode  :character  
#>                                                                             
#>                                                                             
#>                                                                             
#>                                                                             
#>  r2AO_INTSOCI        r2AP_INCOM        r2AQ_FELICID        r2AR_ESTAT       
#>  Length:451         Length:451         Length:451         Length:451        
#>  Class :character   Class :character   Class :character   Class :character  
#>  Mode  :character   Mode  :character   Mode  :character   Mode  :character  
#>                                                                             
#>                                                                             
#>                                                                             
#>                                                                             
#>   r2B_DISFRUT      r2C_IMPORT     r2D_AFECTA        r2E_FACILIT       
#>  Min.   :1.000   Min.   :1.000   Length:451         Length:451        
#>  1st Qu.:2.000   1st Qu.:4.000   Class :character   Class :character  
#>  Median :3.000   Median :5.000   Mode  :character   Mode  :character  
#>  Mean   :2.749   Mean   :4.387                                        
#>  3rd Qu.:3.500   3rd Qu.:5.000                                        
#>  Max.   :5.000   Max.   :5.000                                        
#>  NA's   :4       NA's   :6                                            
#>    r3A_ACCESS      r3B_ACC_EM      r3CA_FAM        r3CB_REC        r3CC_CUL    
#>  Min.   :1.000   Min.   :1.00   Min.   :1.000   Min.   :1.000   Min.   :1.000  
#>  1st Qu.:2.000   1st Qu.:3.00   1st Qu.:2.000   1st Qu.:2.000   1st Qu.:2.000  
#>  Median :3.000   Median :3.00   Median :3.000   Median :3.000   Median :3.000  
#>  Mean   :2.873   Mean   :3.33   Mean   :3.289   Mean   :3.156   Mean   :2.556  
#>  3rd Qu.:3.000   3rd Qu.:4.00   3rd Qu.:4.000   3rd Qu.:4.000   3rd Qu.:3.000  
#>  Max.   :5.000   Max.   :5.00   Max.   :5.000   Max.   :5.000   Max.   :5.000  
#>  NA's   :11      NA's   :18     NA's   :11      NA's   :15      NA's   :14     
#>     r3CD_DEP        r3CE_COM        r3CF_SOC        r3DA_FAM    
#>  Min.   :1.000   Min.   :1.000   Min.   :1.000   Min.   :0.000  
#>  1st Qu.:2.000   1st Qu.:3.000   1st Qu.:3.000   1st Qu.:2.000  
#>  Median :3.000   Median :3.000   Median :4.000   Median :3.000  
#>  Mean   :2.702   Mean   :3.348   Mean   :3.381   Mean   :2.847  
#>  3rd Qu.:4.000   3rd Qu.:4.000   3rd Qu.:4.000   3rd Qu.:4.000  
#>  Max.   :5.000   Max.   :5.000   Max.   :5.000   Max.   :5.000  
#>  NA's   :15      NA's   :14      NA's   :13      NA's   :20     
#>     r3DB_REC        r3DC_CUL        r3DD_DEP        r3DE_COM    
#>  Min.   :0.000   Min.   :0.000   Min.   :0.000   Min.   :0.000  
#>  1st Qu.:2.000   1st Qu.:2.000   1st Qu.:1.000   1st Qu.:2.000  
#>  Median :3.000   Median :3.000   Median :3.000   Median :3.000  
#>  Mean   :2.867   Mean   :2.814   Mean   :2.749   Mean   :2.862  
#>  3rd Qu.:4.000   3rd Qu.:4.000   3rd Qu.:4.000   3rd Qu.:4.000  
#>  Max.   :5.000   Max.   :5.000   Max.   :5.000   Max.   :5.000  
#>  NA's   :22      NA's   :26      NA's   :25      NA's   :22     
#>     r3DF_SOC      r3E_OPCIONES     r3F_ACCESO     r3G_CALIDAD   
#>  Min.   :0.000   Min.   :1.000   Min.   :1.000   Min.   :1.000  
#>  1st Qu.:2.000   1st Qu.:4.000   1st Qu.:3.000   1st Qu.:4.000  
#>  Median :3.000   Median :5.000   Median :4.000   Median :5.000  
#>  Mean   :2.899   Mean   :4.576   Mean   :3.993   Mean   :4.307  
#>  3rd Qu.:4.000   3rd Qu.:5.000   3rd Qu.:5.000   3rd Qu.:5.000  
#>  Max.   :5.000   Max.   :5.000   Max.   :5.000   Max.   :5.000  
#>  NA's   :25      NA's   :1       NA's   :3       NA's   :2      
#>    r3H_ECON          r3I_NOECON          r3JA_OFIC       r3JB_MODOS   
#>  Length:451         Length:451         Min.   :1.000   Min.   :1.000  
#>  Class :character   Class :character   1st Qu.:3.000   1st Qu.:4.000  
#>  Mode  :character   Mode  :character   Median :4.000   Median :5.000  
#>                                        Mean   :4.028   Mean   :4.555  
#>                                        3rd Qu.:5.000   3rd Qu.:5.000  
#>                                        Max.   :5.000   Max.   :5.000  
#>                                        NA's   :20      NA's   :17     
#>    r3JC_COMOD      r3JD_OTROS    r4A_INTERACC         r4B_PERSON   
#>  Min.   :1.000   Min.   :1.000   Length:451         Min.   :1.000  
#>  1st Qu.:4.000   1st Qu.:4.000   Class :character   1st Qu.:2.000  
#>  Median :5.000   Median :5.000   Mode  :character   Median :3.000  
#>  Mean   :4.574   Mean   :4.323                      Mean   :2.854  
#>  3rd Qu.:5.000   3rd Qu.:5.000                      3rd Qu.:4.000  
#>  Max.   :5.000   Max.   :5.000                      Max.   :5.000  
#>  NA's   :14      NA's   :20                         NA's   :12     
#>  r4C_DISCRIM          r4D_MODO          r5A_CAMBIO         r5B_CAMBIO       
#>  Length:451         Length:451         Length:451         Length:451        
#>  Class :character   Class :character   Class :character   Class :character  
#>  Mode  :character   Mode  :character   Mode  :character   Mode  :character  
#>                                                                             
#>                                                                             
#>                                                                             
#>                                                                             
#>    r5C_SUST          r5D_IMP_SUST     r5E_PAGO         r5F_PAGOMAS       
#>  Length:451         Min.   :1.000   Length:451         Length:451        
#>  Class :character   1st Qu.:3.000   Class :character   Class :character  
#>  Mode  :character   Median :4.000   Mode  :character   Mode  :character  
#>                     Mean   :3.966                                        
#>                     3rd Qu.:5.000                                        
#>                     Max.   :5.000                                        
#>                     NA's   :6                                            
#>    r5GA_ARBOL      r5GB_PARK       r5GC_MODO       r5GD_MODO    
#>  Min.   :1.000   Min.   :1.000   Min.   :1.000   Min.   :1.000  
#>  1st Qu.:4.000   1st Qu.:4.000   1st Qu.:4.000   1st Qu.:4.000  
#>  Median :5.000   Median :5.000   Median :5.000   Median :5.000  
#>  Mean   :4.172   Mean   :4.328   Mean   :4.205   Mean   :4.309  
#>  3rd Qu.:5.000   3rd Qu.:5.000   3rd Qu.:5.000   3rd Qu.:5.000  
#>  Max.   :5.000   Max.   :5.000   Max.   :5.000   Max.   :5.000  
#>  NA's   :16      NA's   :12      NA's   :11      NA's   :11     
#>   r6A_INTERC         r6B_CALIDAD    r6CA_ESPERA        r6CB_TRANSB       
#>  Length:451         Min.   :1.000   Length:451         Length:451        
#>  Class :character   1st Qu.:2.000   Class :character   Class :character  
#>  Mode  :character   Median :3.000   Mode  :character   Mode  :character  
#>                     Mean   :2.743                                        
#>                     3rd Qu.:3.000                                        
#>                     Max.   :5.000                                        
#>                     NA's   :198                                          
#>   r6CC_TOTAL        r6D_DIFICULTA       r6E_HERRAM           r6F_INFO    
#>  Length:451         Length:451         Length:451         Min.   :1.000  
#>  Class :character   Class :character   Class :character   1st Qu.:3.000  
#>  Mode  :character   Mode  :character   Mode  :character   Median :3.000  
#>                                                           Mean   :3.236  
#>                                                           3rd Qu.:4.000  
#>                                                           Max.   :5.000  
#>                                                           NA's   :15     
#>   r6G_IMP_INFO     r7AA_AUTO        r7AB_EST       r7AC_AUTOP   
#>  Min.   :1.000   Min.   :1.000   Min.   :1.000   Min.   :1.000  
#>  1st Qu.:3.000   1st Qu.:2.000   1st Qu.:2.000   1st Qu.:3.000  
#>  Median :4.000   Median :3.000   Median :3.000   Median :3.000  
#>  Mean   :4.009   Mean   :3.143   Mean   :2.837   Mean   :3.207  
#>  3rd Qu.:5.000   3rd Qu.:4.000   3rd Qu.:4.000   3rd Qu.:4.000  
#>  Max.   :5.000   Max.   :5.000   Max.   :5.000   Max.   :5.000  
#>  NA's   :10      NA's   :10      NA's   :10      NA's   :11     
#>   r7AD_PEATON      r7AE_VERED      r7AF_PARAD     r7AG_ASIENT   
#>  Min.   :1.000   Min.   :1.000   Min.   :1.000   Min.   :1.000  
#>  1st Qu.:2.000   1st Qu.:2.000   1st Qu.:1.000   1st Qu.:1.000  
#>  Median :3.000   Median :3.000   Median :2.000   Median :2.000  
#>  Mean   :3.136   Mean   :2.885   Mean   :2.486   Mean   :2.342  
#>  3rd Qu.:4.000   3rd Qu.:4.000   3rd Qu.:3.000   3rd Qu.:3.000  
#>  Max.   :5.000   Max.   :5.000   Max.   :5.000   Max.   :5.000  
#>  NA's   :10      NA's   :9       NA's   :9       NA's   :9      
#>    r7AH_CLIMA     r7AI_CICLOV     r7AJ_CICLOV      r7AK_BICI    
#>  Min.   :1.000   Min.   :1.000   Min.   :1.000   Min.   :1.000  
#>  1st Qu.:1.000   1st Qu.:1.000   1st Qu.:1.000   1st Qu.:1.000  
#>  Median :2.000   Median :2.000   Median :2.000   Median :2.000  
#>  Mean   :2.159   Mean   :2.174   Mean   :2.267   Mean   :2.371  
#>  3rd Qu.:3.000   3rd Qu.:3.000   3rd Qu.:3.000   3rd Qu.:3.000  
#>  Max.   :5.000   Max.   :5.000   Max.   :5.000   Max.   :5.000  
#>  NA's   :10      NA's   :9       NA's   :9       NA's   :9      
#>    r7BA_AUTO        r7BB_EST       r7BC_AUTOP     r7BD_PEATON   
#>  Min.   :1.000   Min.   :1.000   Min.   :1.000   Min.   :1.000  
#>  1st Qu.:3.000   1st Qu.:3.000   1st Qu.:3.000   1st Qu.:4.000  
#>  Median :4.000   Median :4.000   Median :4.000   Median :5.000  
#>  Mean   :3.526   Mean   :3.588   Mean   :4.048   Mean   :4.434  
#>  3rd Qu.:5.000   3rd Qu.:5.000   3rd Qu.:5.000   3rd Qu.:5.000  
#>  Max.   :5.000   Max.   :5.000   Max.   :5.000   Max.   :5.000  
#>  NA's   :12      NA's   :12      NA's   :11      NA's   :11     
#>    r7BE_VERED      r7BF_PARAD     r7BG_ASIENT     r7BH_CLIMA     r7BI_CICLOV   
#>  Min.   :1.000   Min.   :1.000   Min.   :1.00   Min.   :1.000   Min.   :1.000  
#>  1st Qu.:4.000   1st Qu.:4.000   1st Qu.:4.00   1st Qu.:4.000   1st Qu.:4.000  
#>  Median :5.000   Median :5.000   Median :5.00   Median :5.000   Median :5.000  
#>  Mean   :4.473   Mean   :4.434   Mean   :4.27   Mean   :4.443   Mean   :4.443  
#>  3rd Qu.:5.000   3rd Qu.:5.000   3rd Qu.:5.00   3rd Qu.:5.000   3rd Qu.:5.000  
#>  Max.   :5.000   Max.   :5.000   Max.   :5.00   Max.   :5.000   Max.   :5.000  
#>  NA's   :11      NA's   :11      NA's   :11     NA's   :11      NA's   :11     
#>   r7BJ_CICLOV     r7BK_BICI       r8A_ACCESO      r8B_OPORT      r8C_ACC_COM   
#>  Min.   :1.00   Min.   :1.000   Min.   :1.000   Min.   :1.000   Min.   :1.000  
#>  1st Qu.:4.00   1st Qu.:4.000   1st Qu.:1.000   1st Qu.:2.000   1st Qu.:3.000  
#>  Median :5.00   Median :5.000   Median :3.000   Median :3.000   Median :4.000  
#>  Mean   :4.48   Mean   :4.244   Mean   :2.713   Mean   :2.725   Mean   :3.927  
#>  3rd Qu.:5.00   3rd Qu.:5.000   3rd Qu.:4.000   3rd Qu.:3.000   3rd Qu.:5.000  
#>  Max.   :5.00   Max.   :5.000   Max.   :5.000   Max.   :5.000   Max.   :5.000  
#>  NA's   :11     NA's   :12      NA's   :15      NA's   :11      NA's   :15     
#>   r8D_EMPLEO         r8E_TIEMPO        r8F_HORARIOS        r8G_GASTO        
#>  Length:451         Length:451         Length:451         Length:451        
#>  Class :character   Class :character   Class :character   Class :character  
#>  Mode  :character   Mode  :character   Mode  :character   Mode  :character  
#>                                                                             
#>                                                                             
#>                                                                             
#> 
```

You’ll still need to render `README.Rmd` regularly, to keep `README.md`
up-to-date. `devtools::build_readme()` is handy for this. You could also
use GitHub Actions to re-render `README.Rmd` every time you push. An
example workflow can be found here:
<https://github.com/r-lib/actions/tree/v1/examples>.

You can also embed plots, for example:

<img src="man/figures/README-pressure-1.png" width="100%" />

In that case, don’t forget to commit and push the resulting figure
files, so they display on GitHub and CRAN.
