---
title: Abour Purchases (Collapsible)
layout: barebones
app_name: "Pocket Shruti Box"
app_full_name: "Pocket Shruti Box—The Carnatic Tambura"
email: "shrutibox@kuyil.org"
premium: "premium"
switch_to_premium: 'use a premium feature'
---

<div class="container">
  <div class="row">
    <div class="col-xs-4 col-xs-offset-4 col-md-2 col-md-offset-5">
      <img class="img-responsive" src="/images/shrutibox_seal.svg" alt="{{ page.app_full_name }}"/>
    </div>
  </div>

  <div id="accordion">
    {% include faq/payment_modes.html %}
    {% include faq/post_purchase_apprehensions.html %}
    {% include faq/i_dont_like_it.html %}
  </div>
</div>
