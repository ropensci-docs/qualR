# Monitor Ar Parameters

List of Monitor Ar Rio available parameters. Use this to check the
parameters argument in MonitorArRetrieveParam() function. Parameter
names are without diacritics.

## Usage

``` r
monitor_ar_param
```

## Format

A data frame with 18 observations and 3 variables:

- code:

  MonitorAr parameter abbreviation or code.

- name:

  MonitorAr parameter name

- units:

  Parameter units.

## Examples

``` r
monitor_ar_param
#>         code                                name units
#> 1        SO2                  Dioxido de enxofre ug/m3
#> 2        NO2               Dioxido de nitrogenio ug/m3
#> 3         NO              Monoxido de Nitrogenio ug/m3
#> 4        NOx                Oxidos de nitrogenio ug/m3
#> 5       HCNM Hidrocarbonetos Totais menos Metano   ppm
#> 6        HCT              Hidrocarbonetos Totais   ppm
#> 7        CH4                              Metano ug/m3
#> 8         CO                 Monoxido de Carbono   ppm
#> 9         O3                              Ozonio ug/m3
#> 10      PM10                Particulas Inalaveis ug/m3
#> 11     PM2_5          Particulas Inalaveis Finas ug/m3
#> 12     Chuva          Precipitacao Pluviometrica    mm
#> 13      Pres                 Pressao Atmosferica  mbar
#> 14        RS                      Radiacao Solar  W/m2
#> 15      Temp                         Temperatura    ºC
#> 16        UR              Umidade Relativa do Ar     %
#> 17 Dir_Vento                    Direcao do Vento     º
#> 18 Vel_Vento                 Velocidade do Vento   m/s
```
