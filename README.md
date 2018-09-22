# servant-swagger (Aelve fork)

## Changes

* Error codes 400 and 404 are not added automatically (when `QueryParam` or
  `Capture` are used). If your handlers accept some parameters that might be
  unparseable, you should warn the user about the errors by yourself.