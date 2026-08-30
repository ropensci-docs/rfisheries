# Returns landings data from the openfisheries API

The function returns aggregate landings data if no parameters are
supplied. One could get country or species-specific data by specifying
either one of those options. Country must be provided as the `iso3c`
code and species must be supplied as a3_code. Supporting functions
`country_codes` and `species_codes` provide that data and can be
combined to return data for multiple countries or species.

## Usage

``` r
of_landings(country = NA, species = NA, foptions = list())
```

## Arguments

- country:

  Default is `NA`. Download country specific data by specifying the
  ISO-3166 alpha 3 country code.

- species:

  Default is `NA`. Download species specific data by specifying the
  three-letter ASFIS species code

- foptions:

  additional optional parameters

## Value

data.frame

## Examples

``` r
if (FALSE) { # \dontrun{
of_landings()
# Landings by country
of_landings(country = 'CAN')
#landings by species
of_landings(species = 'COD')
} # }
```
