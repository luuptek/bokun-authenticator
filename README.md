# bokun-authenticator

This is a PHP-client to be used with Bokun (bokun.io) JSON API.
https://bokun.github.io/api-docs/#/

Use to authenticate with Bokun API and receive the data via API.

## Using

1. Register with Bokun
2. Setup API key in Bokun
3. Set access key and secret key in Bokun_auth class

```
// METHOD = GET or POST
// JSON_PATH: Check possible variations: https://bokun.github.io/api-docs/#/
$bokun = new Bokun_auth('METHOD', 'JSON_PATH');

// Get data
$data = $bokun->get_bokun_data();
```