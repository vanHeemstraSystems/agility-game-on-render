# 200 - Configuring DNS to Point to Render

At this point, you'll need to work with your DNS provider (here: ) to add ```CNAEM```, ```ANAME```, ```ALIAS``` or ```A``` records pointing to render. We have instructions for common providers below:

**WARNING** Make sure to remove any existing ```AAAA``` records for your domains when you update your DNS settings. ```AAAA``` records map a domain to a corresponding IPv6 record, but Render does not support IPv6 addresses yet. As a result, ```AAAA``` records can interfere with Render hosting your custom domains.

## 100 - Cloudflare

## 200 - Namecheap

## 300 - Other DNS providers (this is us)

See [README.md](./300/README.md)

Once you've updated your DNS records, it can take a few minutes for your domains to be verified on Render. See [Speed up Domain Verification](https://docs.render.com/custom-domains#speed-up-domain-verification) below.

You'll see the domain verification status in green once everything is good to go.

You’re all set! Your custom domains will start pointing to your Render service and we’ll continue to issue and renew TLS certificates for them as long as you’re using Render.
