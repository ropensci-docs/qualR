# CETESB Parameters

List of CETESB QUALAR available parameters and units. Use this to check
the `parameters` argument. Parameter names are without diacritics.

## Usage

``` r
cetesb_param
```

## Format

A data frame with 20 observations and 3 variables:

- name:

  CETESB QUALAR parameter abbreviation and name.

- units:

  Parameter units.

- code:

  Parameter CETESB QUALAR code.

## Examples

``` r
cetesb_param
#>                                          name units code
#> 1                               BEN (Benzeno) ug/m3   61
#> 2                    CO (Monoxido de Carbono)   ppm   16
#> 3                       DV (Direcao do Vento)     º   23
#> 4               DVG (Direcao do Vento Global)     º   21
#> 5                ERT (Enxofre Reduzido Total)   ppb   19
#> 6  HCNM (Hidrocarbonetos Totais menos Metano)     -   59
#> 7                 MP10 (Particulas Inalaveis) ug/m3   12
#> 8          MP2.5 (Particulas Inalaveis Finas) ug/m3   57
#> 9                 NO (Monoxido de Nitrogenio) ug/m3   17
#> 10                NO2 (Dioxido de Nitrogenio) ug/m3   15
#> 11                 NOx (Oxidos de Nitrogenio)   ppb   18
#> 12                                O3 (Ozonio) ug/m3   63
#> 13                PRESS (Pressao Atmosferica)   hPa   29
#> 14               RADG (Radiacao Solar Global)  W/m2   26
#> 15             RADUV (Radiacao Ultra-violeta)  W/m2   56
#> 16                   SO2 (Dioxido de Enxofre) ug/m3   13
#> 17                   TEMP (Temperatura do Ar)    ºC   25
#> 18                              TOL (Tolueno) ug/m3   62
#> 19                UR (Umidade Relativa do Ar)     %   28
#> 20                   VV (Velocidade do Vento)   m/s   24
```
