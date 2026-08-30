# Monitor Ar AQS stations.

List of Monitor Ar Rio air quality stations (AQS) with their codes and
locations. Use this to check the parameters argument in
MonitorArRetrieveParam() function.

## Usage

``` r
monitor_ar_aqs
```

## Format

A data frame with 8 observation and 6 variables:

- name:

  MonitorAr Program AQS name.

- code:

  MonitorAr Program AQS abbreviation.

- lon:

  MonitorAr Program AQS longitude.

- lat:

  MonitorAr Program AQS latitude.

- x_utm_sirgas2000:

  MonitorAr Program AQS longitude in SIRGAS 2000 (EPSG:31983).

- y_utm_sirgas2000:

  MonitorAr Program AQS latitude in SIRGAS 2000 (EPSG:31983).

## Examples

``` r
monitor_ar_aqs
#>                         name code       lon       lat x_utm_sirgas2000
#> 1 ESTACAO PEDRA DE GUARATIBA   PG -43.62901 -23.00438         640506.0
#> 2              ESTACAO BANGU   BG -43.47107 -22.88791         656828.8
#> 3       ESTACAO CAMPO GRANDE   CG -43.55652 -22.88625         648064.5
#> 4              ESTACAO IRAJA   IR -43.32684 -22.83162         671696.6
#> 5         ESTACAO COPACABANA   AV -43.18048 -22.96500         686537.0
#> 6             ESTACAO TIJUCA   SP -43.23266 -22.92492         681240.2
#> 7      ESTACAO SAO CRISTOVAO   SC -43.22175 -22.89777         682395.8
#> 8             ESTACAO CENTRO   CA -43.17815 -22.90834         686853.7
#>   y_utm_sirgas2000
#> 1          7455338
#> 2          7468075
#> 3          7468346
#> 4          7474147
#> 5          7459198
#> 6          7463703
#> 7          7466695
#> 8          7465470
```
