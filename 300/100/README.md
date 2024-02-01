# 100 - Adding a Custom Domain

First, if you haven't already, create a web service on Render. See Quickstarts in the navigation bar for sample applications.

**NOTE**: We already have a web service, [Agility Game: Kener](https://dashboard.render.com/web/srv-cmt5k5ol6cac73areiq0).

Then go to the **Settings** tab for your service. You'll see the **Custom Domains** section further down the page.

Click **Add Cusotom Domain** and enter your custom domain.

- If you add a domain containing ```www```, we automatically add the version of your domain without the ```www``` and redirect it to the ```www``` version.

- If you enter a root domain (also called an apex domain) without the ```www``, we automatically add the ```www``` version and redirect it to the root domain.

Here we enter: **status.agility-game.com**, hence a root domain.

