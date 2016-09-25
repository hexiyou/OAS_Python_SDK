# OAS Python SDK

## Requirements

* Python 2.6(included) to 3.0(not included)
* yaml
* ordereddict

## Setup

### Setup through pip
```
    $ pip install -r requirements.txt
    $ pip install oassdk
```

### Setup through source
```
	$ python setup.py install
```

## Update Logs

### Version 0.2.4

* debug no-support of python version 2.7.0

### Version 0.2.4

* add `osshost` config support to help setting default OSS host
  for oascmd.py `cp`

### Version 0.2.3

* add push-to-oss and pull-from-oss job

### Version 0.2.2

* fix parsing size of type long error

### Version 0.2.1

* oascmd require python2.7 to 3.0
* fix bug of part size compute error

### Version 0.2.0

* use tree-etag to verify the data
* support some new feature, such as 40T archive
* improve the oas_cmd.py
* fix some bug

### Version 0.1.9

* fix bug of exception throwing in low level api
* remove requirement of simplejson
* support python 2.6
* use logging to record status instead of print



