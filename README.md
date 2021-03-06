🔥 `drake` for Workflow Happiness 🔥
==================================

This is an intro to the [`drake`](https://github.com/ropensci/drake) R
package for data pipelining. It might be useful for you if you’re
interested in reproducibility after you make changes to your code.

The talk is split into two parts:
[**slides**](https://aedobbyn.github.io/nyc-fires/index.html), and a
[**live coding
walkthrough**](https://github.com/aedobbyn/nyc-fires/blob/master/live_code.md).
The latter is meant to be stepped through in an R session rather than
knit.

### Why all the fire emoji tho

…especially if the whole point of `drake` is that you don’t need to burn
it all down and start from scratch each time?

This talk is motivated by the [**NYCFireWire Twitter
account**](https://twitter.com/NYCFireWire) with an assist from
[Gritty](https://youtu.be/FNt0anp7WK8?t=8) at a [burner
account](https://twitter.com/didntstartit).

It relies on the [**`rtweet`**](https://github.com/mkearney/rtweet) and
[**`ggmap`**](https://github.com/dkahle/ggmap) packages, so to be able
to run it in full you’ll need a [Twitter API access
token](https://rtweet.info/articles/auth.html) and [Google Maps
Geocoding API
key](https://developers.google.com/maps/documentation/geocoding/intro#Geocoding).

### Other things you might want to know

-   All functions live in
    [`didnt_start_it.R`](https://github.com/aedobbyn/nyc-fires/blob/master/R/didnt_start_it.R).

-   Feel free to use any and all of the data, including the
    [raw](https://github.com/aedobbyn/nyc-fires/blob/master/data/raw/lots_o_fires.csv)
    and
    [geocoded](https://github.com/aedobbyn/nyc-fires/blob/master/data/derived/dat.csv)
    tweet motherlode.

<!-- <p align="right"> -->
<img src="./img/happy_drake.jpg" height="200" align="right">
<!-- </p> -->

-   The best resources on `drake` remain the [`drake`
    manual](https://ropenscilabs.github.io/drake-manual/) and
    [Will](https://twitter.com/wmlandau)
    [Landau](https://github.com/wlandau) :)
