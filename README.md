# PyUaaClient
Simple python client for UAA on [Predix](https://www.predix.io)

## Install
```
pip install PyUaaClient
```

## Example 
```
uaaClient = UaaClient('<UAA Instance URL', '<client ID>', 'client secret')
token = uaaClient.getToken()
```
