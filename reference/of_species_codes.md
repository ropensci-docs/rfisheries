# Download species data including three-letter ASFIS species code.

Returns a data frame with scientific_name, taxocode, a3_code, isscaap,
and English name. The a3_code is required by
[`landings`](https://docs.ropensci.org/rfisheries/reference/country_codes-deprecated.md)
to return species specific landing data.

## Usage

``` r
of_species_codes(foptions = list())
```

## Arguments

- foptions:

  additional optional parameters

## Value

data.frame

## Examples

``` r
if (FALSE) { # \dontrun{
of_species_list <- of_species_codes()
} # }
```
