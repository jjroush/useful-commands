# useful-commands
Useful bash commands I use.

### SHA256 Hash and base64 encode string

echo -n 'string_goes_here' | openssl dgst -binary -sha256 | openssl base64
