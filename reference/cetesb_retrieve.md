# Download a single parameter from CETESB QUALAR system

This function download one parameter from one air quality stations (AQS)
of CETESB AQS network. It will pad out the date with missing data with
NA.

## Usage

``` r
cetesb_retrieve(
  username,
  password,
  pol_code,
  aqs_code,
  start_date,
  end_date,
  verbose = TRUE,
  to_csv = FALSE
)
```

## Arguments

- username:

  User name of CETESB QUALAR

- password:

  User name's password of CETESB QUALAR

- pol_code:

  Code of parameter

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

## Value

data.frame with the selected parameter information

## Examples

``` r
if (FALSE) { # \dontrun{
# Downloading Ozone information from Pinheiros AQS
# from January first to 7th of 2020
my_user_name <- "John Doe"
my_pass_word <- "drowssap"
o3_code <- 63  # Check with cetesb_param
pin_code <- 99 # Check with cetesb_aqs
start_date <- "01/01/2020"
end_date <- "07/01/2020"

pin_o3 <- cetesb_retrieve(my_user_name, my_pass_word, o3_code, pin_code,
                          start_date, end_date)

} # }
```
