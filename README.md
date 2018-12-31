#####This repository contains all fault localizaiton results for the paper submitted to TOSEM.

#####Each sub-directory contains the detailed results for:

* *assign*: only use predicates from  `scalar-pairs` of SD.
* *branches*: only use predicates from `branches` of SD.
* *return*: only use predicates from `returns` of SD.
* *branches_assign*: use predicates from both `branches` and `scalar-pairs`.
* *method*: collect predicate coverage data at `method` level.
* *linear_sd_0.x*: linearly combine predicate scores of SBFL and SD with coeffecient `\alpha=0.x`.