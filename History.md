
0.1.2 / 2017-08-12
==================

  * Add missing API method - returnLendingHistory

0.1.0 / 2017-07-03
==================

  * If no callback is provided, a Promise object is returned. (close #11)
  * Update old dependencies and create package-lock.
  * Add standard and pre-commit configs and scripts.
  * Fix WS 3.0 bug in autobahn
  * Add optional parameter to returnCompleteBalances
  * Merge pull request #13 from CjS77/data_on_err
  * Always include data in error callback

0.0.10 / 2016-08-27
==================

  * Fix "missing callback" error on returnTicker (close #9, close #6)

0.0.9 / 2016-07-12
==================

  * Update methods in the README.md

0.0.8 / 2016-07-12
==================

  * Add returnOrderTrades (close #8)
  * standardjs

0.0.7 / 2016-03-15
==================

  * Fix the reference in cfg.params (closes #3)
  * Fix the reference problem in options param (close #2)

0.0.6 / 2016-03-12
==================

  * Module nonce removed and replaced by an internal function. Fix the bug that repeat the incremental number in nonce module. (close #2)
  * Update gitignore

0.0.5 / 2016-03-09
==================

  * Add statusCode check in request callback (close #1)

v0.0.4 / 2016-03-07
===================

  * Code syntax improvements
  * README improvements
  * Move licence to README and delete LICENCE file
  * Delete .npmignore
  * Add new tags in package.json

v0.0.3 / 2016-03-06
===================

  * Add User-Agent in request and code improvements

v0.0.2 / 2016-03-06
===================

  * Update README.md

v0.0.1 / 2016-03-06
===================

  * Update README.md
  * Add LICENCE
  * Add README
  * Add push method using autobahn
  * Fix exports and code improvements
  * Add .npmignore
  * First version
