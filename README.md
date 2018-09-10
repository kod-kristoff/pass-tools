# pass-tools
Scripts for using pass.

## Available tool
* `pass-curl`
    - Script for using pass with curl.

## Example
```
pass-curl PASSNAME USER 'https://example.com'
```
is expanded to
```
curl --user USER:$(pass show PASSNAME) 'https://example.com'
```
