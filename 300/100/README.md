# 100 - Adding a Custom Domain

First, if you haven't already, create a web service on Render. See Quickstarts in the navigation bar for sample applications.

## 100 - Kener

**NOTE**: We already have a web service, [Agility Game: Kener](https://dashboard.render.com/web/srv-cmt5k5ol6cac73areiq0).

Then go to the **Settings** tab for your service. You'll see the **Custom Domains** section further down the page.

Click **Add Custom Domain** and enter your custom domain.

- If you add a domain containing ```www```, we automatically add the version of your domain without the ```www``` and redirect it to the ```www``` version.

- If you enter a root domain (also called an apex domain) without the ```www```, we automatically add the ```www``` version and redirect it to the root domain.

Here we enter: **status.agility-game.com**, hence **not** a root domain, but a subdomain.

You should now see the following message with instructions to update DNS settings with your DNS provider. See next section for how to do this.

**status.agility-game.com**

DNS update needed: **Verify** **Delete**

Add a CNAME record for **status** pointing to [agility-game-kener.onrender.com](https://agility-game-kener.onrender.com)

[DNS configuration instructions](https://docs.render.com/custom-domains#configuring-dns-to-point-to-render)

## 200 - Ghost

**NOTE**: We already have a web service, [Agility Game: Ghost](https://dashboard.render.com/web/srv-???????????).

Then go to the **Settings** tab for your service. You'll see the **Custom Domains** section further down the page.

Click **Add Custom Domain** and enter your custom domain.

- If you add a domain containing ```www```, we automatically add the version of your domain without the ```www``` and redirect it to the ```www``` version.

- If you enter a root domain (also called an apex domain) without the ```www```, we automatically add the ```www``` version and redirect it to the root domain.

Here we enter: **blog.agility-game.com**, hence **not** a root domain, but a subdomain.

You should now see the following message with instructions to update DNS settings with your DNS provider. See next section for how to do this.

**blog.agility-game.com**

DNS update needed: **Verify** **Delete**

Add a CNAME record for **blog** pointing to [agility-game-ghost.onrender.com](https://agility-game-ghost.onrender.com)

[DNS configuration instructions](https://docs.render.com/custom-domains#configuring-dns-to-point-to-render)
