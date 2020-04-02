This directory contains the client for the [Prometheus HTTP API](http://prometheus.io/docs/querying/api/).
It allows you to write Go applications that query time series data
from a Prometheus server.

It is still in considered EXPERIMENTAL, outside the normal SemVer guarantee —
breaking changes here will _not_ trigger a new major release.  Therefore it's
recommended to pin/vendor a specific commit and upgrade manually.

godoc:
https://godoc.org/github.com/prometheus/client_golang/api
https://godoc.org/github.com/prometheus/client_golang/api/prometheus/v1
(used together, see usage examples in the latter)
