# CETESB AQS station latitude and longitude

List of CETESB QUALAR air quality stations (AQS) latitudes and
longitudes. Use this to check the AQS `aqs_code` argument in
CetesbRetrieveParam() function. AQS names are without diacritics.

## Usage

``` r
cetesb_aqs
```

## Format

A data frame with 74 observations and 5 variables:

- name:

  CETESB AQS name.

- code:

  CETESB AQS code in QUALAR System.

- lat:

  CETESB AQS latitude.

- lon:

  CETESB AQS longitude.

- loc:

  CETESB AQS location.

## Examples

``` r
cetesb_aqs
#>                          name code       lat       lon       loc
#> 1                   Americana  290 -22.72425 -47.33955  Interior
#> 2    Americana-Vila Sta Maria  105 -22.72425 -41.33955  Interior
#> 3                   Araçatuba  107 -21.18684 -50.43932  Interior
#> 4                  Araraquara  106 -21.78252 -48.18583  Interior
#> 5                       Bauru  108 -22.32661 -49.09276  Interior
#> 6                     Cambuci   90 -23.56771 -46.61227      <NA>
#> 7             Campinas-Centro   89 -22.90252 -47.05721  Interior
#> 8           Campinas-Taquaral  276 -22.87462 -47.05897  Interior
#> 9            Campinas-V.União  275 -22.94673 -47.11928  Interior
#> 10              Capão Redondo  269 -23.66836 -46.78004 São Paulo
#> 11                Carapicuíba  263 -23.53140 -46.83578      MASP
#> 12                  Catanduva  248 -21.14194 -48.98308  Interior
#> 13                     Centro   94 -23.54781 -46.64241      <NA>
#> 14            Cerqueira César   91 -23.55354 -46.67270 São Paulo
#> 15 Cid.Universitária-USP-Ipen   95 -23.56634 -46.73741 São Paulo
#> 16                  Congonhas   73 -23.61632 -46.66347 São Paulo
#> 17             Cubatão-Centro   87 -23.87903 -46.41848     Coast
#> 18           Cubatão-V.Parisi   66 -23.84942 -46.38868     Coast
#> 19       Cubatão-Vale do Mogi  119 -23.83159 -46.36957     Coast
#> 20                    Diadema   92 -23.68588 -46.61162      MASP
#> 21         Grajaú-Parelheiros   98 -23.77627 -46.69696 São Paulo
#> 22              Guaratinguetá  289 -22.80192 -45.19112  Interior
#> 23                  Guarulhos  118 -23.46321 -46.49621      MASP
#> 24   Guarulhos-Paço Municipal  264 -23.45553 -46.51853      MASP
#> 25         Guarulhos-Pimentas  279 -23.44012 -46.40995      MASP
#> 26                 Ibirapuera   83 -23.59184 -46.66069 São Paulo
#> 27                 Interlagos  262 -23.68051 -46.67504 São Paulo
#> 28             Itaim Paulista  266 -23.50155 -46.42074 São Paulo
#> 29                   Itaquera   97 -23.58001 -46.46665 São Paulo
#> 30                    Jacareí  259 -23.29420 -45.96823  Interior
#> 31                        Jaú  110 -22.29862 -48.56746  Interior
#> 32                    Jundiaí  109 -23.19200 -46.89710  Interior
#> 33                       Lapa   84 -23.50897 -46.70122 São Paulo
#> 34                    Limeira  281 -22.56360 -47.41431  Interior
#> 35    Marg.Tietê-Pte Remédios  270 -23.51871 -46.74332 São Paulo
#> 36                    Marília  111 -22.19981 -49.95997  Interior
#> 37                       Mauá   65 -23.66855 -46.46600      MASP
#> 38            Mogi das Cruzes  287 -23.51817 -46.18686      <NA>
#> 39                      Mooca   85 -23.54973 -46.60042 São Paulo
#> 40             N.Senhora do Ó   96 -23.48010 -46.69205 São Paulo
#> 41                     Osasco  120 -23.52672 -46.79208      MASP
#> 42          Parque D.Pedro II   72 -23.54485 -46.62768 São Paulo
#> 43                   Paulínia  117 -22.77232 -47.15484  Interior
#> 44               Paulínia Sul  112 -22.78681 -47.13656  Interior
#> 45     Paulínia-Sta Terezinha  291 -22.78021 -41.11390  Interior
#> 46                      Perus  293 -23.41321 -46.75605 São Paulo
#> 47            Pico do Jaraguá  284 -23.45627 -46.76610 São Paulo
#> 48                  Pinheiros   99 -23.56146 -46.70202 São Paulo
#> 49                 Piracicaba  113 -22.70122 -47.64965  Interior
#> 50            Pirassununga-EM  268 -22.00771 -47.42756      <NA>
#> 51        Presidente Prudente  114 -22.11994 -51.40878      <NA>
#> 52             Ribeirão Preto  288 -21.15394 -47.82848  Interior
#> 53    Ribeirão Preto-Ipiranga  115 -21.15394 -47.82848  Interior
#> 54     Rio Claro-Jd.Guanabara  292 -22.43906 -47.58144  Interior
#> 55            S.André Capuava  100 -23.63980 -46.49164      MASP
#> 56             S.André-Centro  101 -23.64562 -46.53633      MASP
#> 57     S.André-Paço Municipal  254 -23.65699 -46.53092      <NA>
#> 58          S.Bernardo-Centro  272 -23.69867 -46.54623      MASP
#> 59       S.Bernardo-Paulicéia  102 -23.67135 -46.58467      MASP
#> 60              S.José Campos   88 -23.18789 -45.87120  Interior
#> 61  S.José Campos-Jd.Satélite  277 -23.22365 -45.89080  Interior
#> 62  S.José Campos-Vista Verde  278 -23.18370 -45.83090  Interior
#> 63          S.Miguel Paulista  236 -23.49853 -46.44480      <NA>
#> 64            Santa Gertrudes  273 -22.45996 -47.53630  Interior
#> 65                    Santana   63 -23.50599 -46.62896 São Paulo
#> 66                Santo Amaro   64 -23.65498 -46.71000 São Paulo
#> 67                     Santos  258 -23.96306 -46.32117     Coast
#> 68      Santos-Ponta da Praia  260 -23.98130 -46.30051     Coast
#> 69         São Caetano do Sul   86 -23.61844 -46.55635      MASP
#> 70      São José Do Rio Preto  116 -20.78469 -49.39828  Interior
#> 71              São Sebastião  294 -23.80520 -45.40007   Litoral
#> 72                   Sorocaba   67 -23.50243 -47.47903  Interior
#> 73            Taboão da Serra  103 -23.60932 -46.75829      MASP
#> 74                      Tatuí  256 -23.36075 -47.87080  Interior
#> 75                    Taubaté  280 -23.03235 -45.57581  Interior
```
