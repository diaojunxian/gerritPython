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

password = "{http password}"

url = "{url}"

path = "/projects/{project-name}}"


response = gerritpy.get_http(url, path, username, password)

print json.dumps(response, indent=4)
```
You can get `http password` from your gerrit account,`settings`-`HTTP Password`,and then generate your password.

## TODO

```
POST api
PUT api
```

## Contributors

junxiandiao@gmail.com

## LICENSE

[MIT](https://github.com/diaojunxian/gerritPython/blob/master/LICENSE)
