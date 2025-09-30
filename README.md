# byod-proxy


BYOD with Caddy(Bring your own domain)

People can point their domains to your server IP and it'll automatically issue SSL's. (Can be abused by sending sketchy Host headers, stay safe :)  )

This setup assumes that bareserver/website is running on port 8080.

Adjust that accordingly and you have BYOD.

This is not a good robust setup, but it should work, you might get DDoS'd or ratelimited
