# 200 - Configuring www and other subdomains (this is us)

For non-root domains, you should always add a ```CNAME``` record pointing to your app’s Render subdomain. For example, if your Render subdomain is ```example.onrender.com``` and your custom domain is ```www.example.com```, you should add a ```CNAME``` record for ```www``` and point it to ```example.onrender.com```.

In our case, our Render subdomain is ```agility-game-kener.onrender.com``` and our custom domain is ```status.agility-game.com```, we should add a ```CNAME``` record for ```status``` and point it to ```agility-game-kener.onrender.com```.

![CName_status_agility_game_com](https://github.com/vanHeemstraSystems/agility-game-on-render/assets/1499433/869eda4e-716d-474d-b88a-b7d0271955cd)

DNS Records at https://cp.pcextreme.nl/auroradns/zones/89748cc1-dbeb-4937-aff5-ce87a1d0ba50

Ooops.. we get an error when we pass the verification:

![CName_status_certificate_issue](https://github.com/vanHeemstraSystems/agility-game-on-render/assets/1499433/23439e60-4006-4c7c-9973-d13fdb7297e3)

Let's contact Render's Support...

Hold on ... ! 

After a few minutes, the issue resolved itself. Refresh the browser and witness that the certifacte has been issued successfully. 

![CName_status_certificate_issued](https://github.com/vanHeemstraSystems/agility-game-on-render/assets/1499433/7a16a195-e5a5-4d5a-a9e8-0e58cef78b33)

Hooray!!

**DO NOT FORGET TO ENABLE THE TRANSFER LOCK AGAIN FOR agility-game.com AT versio!
