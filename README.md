
# *nba_py - [stats.nba.com](http://stats.nba.com) API for python*

#### This is a fork of seemethere's original nba_py, which seems to be abandoned and is no longer working. Minor changes were made to get it back to working condition. But has not been extensively tested.
#### [stats.nba.com Endpoint Documentation](https://github.com/seemethere/nba_py/wiki/stats.nba.com-Endpoint-Documentation)

Stable version: **v0.1a1**

This branches version: **v0.1a2**

## Summary
A python facing API for stats.nba.com (Still in heavy development)


Originally based off [https://github.com/bradleyfay/NBAStats](https://github.com/bradleyfay/NBAStats)

## Installation
NOTE: Developmental builds, are by no means stable If you want the stable version use:

```
$ pip install nba_py
```

Else:
- Download from source (git clone, zipped package)
- Run from the root directory:

```
$ pip install .
```

## Requirements [![Requires.io](https://img.shields.io/requires/github/seemethere/nba_py.svg?style=flat-square)](https://requires.io/github/seemethere/nba_py/requirements/?branch=master)
- [requests](http://www.python-requests.org/en/latest/)

## Nice to have
Pandas is nice to have because it'll put the data in an easy to manage object, but it is by no means necessary. All data, if pandas is not installed is returned in a nice json list format with headers!
- [pandas](http://pandas.pydata.org/) [(Installation Help)](https://github.com/seemethere/nba_py/wiki/Installing-pandas)

Requests-cache is nice to have when you are downloading very large datasets so that subsequent downloads take much less time, but again, it is by no means necessary.
- [requests-cache](https://github.com/reclosedev/requests-cache)

## Completed work
- See the [wiki](https://github.com/seemethere/nba_py/wiki/Completed-Work-Log)

## Planned development
### 1. Documentation
- All around documentation not only of nba_py but also stats.nba.com (it's pretty nonexistent)

### ~~2. Map rest of API~~ (Completed)
