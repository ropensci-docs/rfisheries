# Download full list of ISO-3166 alpha 3 country code.

Function returns a data frame with country name and `iso3c` code which
is required by the
[`landings`](https://docs.ropensci.org/rfisheries/reference/country_codes-deprecated.md)
function to return country specific data

## Usage

``` r
of_country_codes(foptions = list())
```

## Arguments

- foptions:

  additional curl options

## Value

data.frame

## Examples

``` r
if (FALSE) { # \dontrun{
of_country_codes()
} # }
```
