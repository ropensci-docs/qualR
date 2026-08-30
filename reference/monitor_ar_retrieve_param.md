# Download air quality and meteorology information from MonitorAr-Rio

This function download air quality and meteorology measurements from
MonitorAr-Rio program from Rio de Janeiro city.

## Usage

``` r
monitor_ar_retrieve_param(
  start_date,
  end_date,
  aqs_code,
  parameters,
  to_local = TRUE,
  verbose = TRUE,
  to_csv = FALSE,
  csv_path = ""
)
```

## Arguments

- start_date:

  Date to start downloading in dd/mm/yyyy

- end_date:

  Date to end downloading in dd/mm/yyyy

- aqs_code:

  AQS code

- parameters:

  Parameters to download. It can be a vector with many parameters.

- to_local:

  Date information in local time. TRUE by default.

- verbose:

  Print query summary.

- to_csv:

  Creates a csv file. FALSE by default

- csv_path:

  Path to save the csv file.

## Value

data.frame with the selected parameter information

## Examples

``` r
if (FALSE) { # \dontrun{
# Downloading Ozone information from Centro AQS
# from February of 2019
date_start <- "01/02/2019"
date_end <- "01/03/2019"
aqs_code <- "CA"
param <- "O3"
ca_o3 <- monitor_ar_retrieve_param(date_start, date_end, aqs_code, param)

} # }
```
