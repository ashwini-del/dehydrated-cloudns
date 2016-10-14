# dehydrated-cloudns

[dehydrated](https://github.com/lukas2511/dehydrated) hook for ClouDNS.

This script depends on [bind-tools (host)](http://www.isc.org/software/bind), [curl](https://curl.haxx.se/) and [jq](https://stedolan.github.io/jq/).

To use it, just export environment variables, and make [dehydrated](https://github.com/lukas2511/dehydrated) use `hook.sh` as hook:

    $ export CLOUDNS_AUTH_ID="<auth-id here>"
    $ export CLOUDNS_AUTH_PASSWORD="<auth-password here>"

Sub-users are not supported.
