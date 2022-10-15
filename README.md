# With extra index:

## Pants:

* Generate lockfile from clean: ~2m20
* Incremental generate lockfile: Fails after ~1m34s -- bug report filed.
* Run from clean: ~3m30
* Run without new deps: ~6s

## PDM:

* Generate lockfile from clean: 14m (!)
* Incremental generate lockfile: 1m
* Install: 1m

## Poetry:

* Generate lockfile from clean: 11m15s
* Incremental generate lockfile: 42s
* Install clean: 1ms10s
