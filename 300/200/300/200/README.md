# 200 - Configuring www and other subdomains (this is us)

For non-root domains, you should always add a ```CNAME``` record pointing to your app’s Render subdomain. For example, if your Render subdomain is ```example.onrender.com``` and your custom domain is ```www.example.com```, you should add a ```CNAME``` record for ```www``` and point it to ```example.onrender.com```.

In our case, our Render subdomain is ```agility-game-kener.onrender.com``` and our custom domain is ```status.agility-game.com```, we should add a ```CNAME``` record for ```status``` and point it to ```agility-game-kener.onrender.com```.
