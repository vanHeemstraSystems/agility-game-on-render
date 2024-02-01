# 200 - Configuring DNS to Point to Render

At this point, you'll need to work with your DNS provider (here: ) to add ```CNAEM```, ```ANAME```, ```ALIAS``` or ```A``` records pointing to render. We have instructions for common providers below:

**WARNING** Make sure to remove any existing ```AAAA``` records for your domains when you update your DNS settings. ```AAAA``` records map a domain to a corresponding IPv6 record, but Render does not support IPv6 addresses yet. As a result, ```AAAA``` records can interfere with Render hosting your custom domains.

## 100 - Cloudflare

## 200 - Namecheap

## 300 - Other DNS providers (this is us)

See [README.md](./300/README.md)
