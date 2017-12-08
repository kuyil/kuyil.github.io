---
title: Abour Purchases
layout: barebones_white_margins
app: "Sadhakam"
email: "sadhakam@kuyil.org"
---

<div class="row">
  <div class="col-xs-4 col-xs-offset-4 col-md-2 col-md-offset-5">
    <img class="img-responsive" src="/images/sadhakam_seal.svg" alt="{{ page.app }} Carnatic Tuner"/>
  </div>
</div>

## Buying

{% include faq/payment_modes.markdown %}

### <a id="troubleshoot_premium"></a>I purchased, still some levels/exercises don't open?

If you have purchased but unable to access premium exercises, it is a temporary issue caused by one of the following reasons. Did you do any of these?
* Ran a cleaner to free up space in your device?
* Cleared {{ page.app }} or Play store app's cache/data?
* Added a different google account to your phone, or switched user?
* Did your phone face low memory issue recently?

As you may know, purchases are handled by Google Play. When you open {{ page.app }}, it will ask Google Play whether you have bought or rented the exercises in level. If Google Play says yes, {{ page.app }} will enable them. Google Play usually saves your purchases in your device so that your purchases would work even when you are offline. The purchase info may not be readily available when you switch google accounts or clear Play store's cache/data.

#### If you are a subscriber:

Ensure that the subcription is still active:
* Open Google Play, open its menu -> accounts -> Subscriptions. You should see an active subscription for {{ page.app }}.

If you don't see an active subscription for {{ page.app }}, the reason could be one of these two:
* **Your subscription is expired**: Please renew your subscription or buy the *One-Time* feature to get permanent access to all exercises.
* **You are using a different Google account**: Open Google Play, open its menu -> accounts -> Order History, you should see details of your previous payments to {{ page.app }}
* **Not logged into Google Play, or cache is cleared**: Log in to Google Play with the Google account with which you purchased {{ page.app }} subscription. Verify the subscription is active as mentioned above. 

If you see {{ page.app }}'s subscription being active on your account, open {{ page.app }}, preferably with internet ON. Wait for a moment, and launch any exercise. It should work.

#### If you have made one-time purchase:

* Make sure you are connected to internet. (You'll need internet this one time to retrieve and verify your purchase. Later, you can continue to use the app do all the exercises without internet connection)
* Swipe apps from recent apps list, especially Google Play and {{ page.app }}.
* Open Google Play, open its menu -> accounts -> Order History. You should see {{ page.app }}'s Onetime purchase in your Google Play's order history. If NOT, go back to Google Play's menu, choose the Google account wiht which you made the purchase and login.
* open {{ page.app }}, preferably with internet ON. Wait for a moment, and switch to "All" swarams mode. It should work.
* If you use cleaner app, please exclude {{ page.app }} and Google Play to prevent this problem happening again.


{% include faq/post_purchase_apprehensions.markdown %}

{% include faq/footer.markdown %}
