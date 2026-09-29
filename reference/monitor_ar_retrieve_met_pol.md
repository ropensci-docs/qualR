# Download meteorological and pollutant data from Monitor Ar Program

This function download the main meteorological parameters for model
evaluation, together with criteria pollutants for in air quality station
(AQS) of Monitor Ar program. It will pad out the date with missing data
with NA

## Usage

``` r
monitor_ar_retrieve_met_pol(
  start_date,
  end_date,
  aqs_code,
  verbose = TRUE,
  to_local = TRUE,
  to_csv = FALSE,
  csv_path = ""
)
```

## Arguments

- start_date:

  Date to start downloading dd/mm/yyyy

- end_date:

  Date to end downloading dd/mm/yyyy

- aqs_code:

  Code of AQS

- verbose:

  Print query summary

- to_local:

  Date information in local time. TRUE by default.

- to_csv:

  Creates a csv file. FALSE by default.

- csv_path:

  Path to save the csv file.

## Value

data.frame with Temperature (C), Relative Humidity (%), Wind Speed (m/s)
and Direction (degrees), Pressure information (hPa), O3, NO, NO2, NOx,
PM2.5, PM10 and CO information.

## Examples

``` r
if (FALSE) { # \dontrun{
# Downloading main meteorological parameters and criteria pollutant
# from CENTRO AQS from January first to 7th of 2020
start_date <- "01/01/2020"
end_date <- "07/01/2020"
ca_all <- monitor_ar_retrieve_met_pol(start_date, end_date, "CA")
} # }
```
