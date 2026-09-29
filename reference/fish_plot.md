# Plots data for an rfisheries result

Plots data for an rfisheries result

## Usage

``` r
fish_plot(x, linecolor = "steelblue", linesize = 0.9, title = NULL, ...)
```

## Arguments

- x:

  A landings dataset belonging to either a species or a country.

- linecolor:

  Default line color is steelblue

- linesize:

  Default line size is 0.9

- title:

  Plot title. Title is generated based on species or country code.
  Specify one here only if you need something else.

- ...:

  additional arguments

## Examples

``` r
if (FALSE) { # \dontrun{
fish_plot(of_landings(country = 'CAN'))
fish_plot(of_landings(species = 'COD'))
} # }
```
