# NEWS for ggseas


## 0.4.0
* Seasonal adjustment functions will estimate frequency and (for X13 related purposes) start from the data if possible.  If the x variable is a Date rather than numeric, user still needs to provide start and frequency.
* testthat unit tests added


## 0.3.0 (current CRAN version)
* stat_rollapplyr() provides rolling averages
* stat_index() allows time series to be converted to an index with arbitrary reference points
* added index option to stat_seas(), stat_decomp(), stat_stl(), ggsdc() and stat_rollapplyr()


## 0.2.0
* ggsdc() provides decomposition into four facets ala plot(stl(x)) but in ggplot2 approach


## 0.1.0
* First version released to CRAN
* stat_seas(), stat_decomp() and stat_stl() provide seasonal adjustment on the fly