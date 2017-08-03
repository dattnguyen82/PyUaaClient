# PyUaaClient
Simple python client for UAA

# Prerequistes

* [requests](http://docs.python-requests.org/en/master/) 

## Example 
```
uaaClient = UaaClient('<UAA Instance URL', '<client ID>', 'client secret')
token = uaaClient.getToken()
```