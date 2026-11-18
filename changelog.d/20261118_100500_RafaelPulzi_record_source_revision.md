### Enhancements

* Race results in `rally-results-*` now carry `source-revision`, the Elasticsearch build hash the race ran against, so results can be traced back to a commit. Clusters that do not report a build hash are left without the field.
