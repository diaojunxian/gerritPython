## gerrit-python

Gerrit Rest Api Library (not official)

## Installation

```
pip install gerritpy
```

## How to use

```
import gerritpy
import json


username = "{username}"

password = "{http password}}"

url = "{url}"

path = "/projects/{project-name}}"


response = gerritpy.get_http(url, path, username, password)

print json.dumps(response, indent=4)
```

## TODO

`POST` api
`PUT` api

## Contributors

diaojunxian@huami.com

## LICENSE

MIT