# Download list of observation from CETESB QUALAR

This function downloads the parameters in a vector. These parameters can
be both pollutants or meteorological observations for one air quality
station (AQS). It will pad out the date with missing data with NA. This
function requires to have [an
account](https://seguranca.cetesb.sp.gov.br/Home/CadastrarUsuario) in
[CETESB QUALAR](https://qualar.cetesb.sp.gov.br/qualar/home.do).

## Usage

``` r
cetesb_retrieve_param(
  username,
  password,
  parameters,
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

- parameters:

  a character vector with the parameters abbreviations to download

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

data.frame with parameters described in `params` vector

## Examples

``` r
if (FALSE) { # \dontrun{
# Download ozone, nitrogen dioxide, and wind speed
# from Pinheiros AQS, from January first to 7th of 2020

my_user_name <- "John Doe"
my_pass_word <- "drowssap"
pin_code <- 99 # Check with cetesb_aqs
start_date <- "01/01/2020"
end_date <- "07/01/2020"
params <- c("o3","NOX", "VV")

pin_param <- cetesb_retrieve_param(my_user_name, my_pass_word,
                                   params, pin_code,
                                   start_date, end_date)
} # }
```
