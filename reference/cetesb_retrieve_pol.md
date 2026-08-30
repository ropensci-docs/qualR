# Download criteria pollutants from CETESB QUALAR

This function download the criteria pollutants from one air quality
station (AQS) of CETESB AQS network. It will pad out the date with
missing data with NA. This function required to have [an
account](https://seguranca.cetesb.sp.gov.br/Home/CadastrarUsuario) in
[CETESB QUALAR](https://qualar.cetesb.sp.gov.br/qualar/home.do).

## Usage

``` r
cetesb_retrieve_pol(
  username,
  password,
  aqs_code,
  start_date,
  end_date,
  verbose = TRUE,
  to_csv = FALSE,
  csv_path = ""
)
```

## Arguments

- username:

  User name of CETESB QUALAR

- password:

  User name's password of CETESB QUALAR

- aqs_code:

  Code of AQS

- start_date:

  Date to start downloading in dd/mm/yyyy

- end_date:

  Date to end downloading in dd/mm/yyyy

- verbose:

  Print query summary

- to_csv:

  Creates a csv file. FALSE by default

- csv_path:

  Path to save the csv file

## Value

data.frame with O3, NO, NO2, PM2.5, PM10 and CO information. Units are
ug/m3 except for CO which is in ppm, and NOx which is in ppb.

## Examples

``` r
if (FALSE) { # \dontrun{
# Downloading criteria pollutants from Pinheiros AQS
# from January first to 7th of 2020
my_user_name <- "John Doe"
my_pass_word <- "drowssap"
pin_code <- 99 # Check with cetesb_aqs
start_date <- "01/01/2020"
end_date <- "07/01/2020"

pin_pol <- cetesb_retrieve_pol(my_user_name, my_pass_word, pin_code,
                               start_date, end_date)

} # }
```
