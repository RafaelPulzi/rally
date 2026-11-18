### Bug Fixes

* A `composite` operation no longer fails with `unsupported operand type(s) for -: 'NoneType' and 'NoneType'` when `get-async-search` or `delete-async-search` has nothing to do because the preceding `submit-async-search` did not return a search id.
