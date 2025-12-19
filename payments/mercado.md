# Mercado Pago connection

[Mercado Pago](http://mercadopago.com/) is a payment system in Latin America that allows businesses to accept online payments.&#x20;

Follow the steps below to fully connect Mercado Pago to your Wfolio shop.

### Mercado Pago settings

#### Create an application and get credentials

* Open the **Mercado Pago Developer Dashboard**.
* Go to **Your integrations**.
* Click on the **Create application** and give it a name (for example: _“Wfolio shop”_).
* Open the application and go to **Production credentials** in the left menu.
* Complete the required verification steps (usually business information). After approval, Mercado Pago will generate your production credentials.
* **Copy Access Token.**

<figure><img src="../.gitbook/assets/image 101.png" alt=""><figcaption></figcaption></figure>



#### Configure payment notifications

In **Your integrations**, select your application and go to **Webhooks** in the left menu.

* Select **Configure notifications**.
* Select the **Production** tab.
* Enter the address:

```
https://wfolio.com/gateway/integrations/mercadopago/notify
```

* Enable the **Payments** event for **Pages**.
* Click on the **Save configuration**.

When you save the configuration, Mercado Pago will generate a **Webhook Secret Key**. **Copy this key.**

***

### Wfolio settings

* Go to **Wfolio settings → Store settings** and select Mercado Pago.

Paste the **Access Token** from Production credentials and **Webhook Secret Key** from Webhooks configuration.

<figure><img src="../.gitbook/assets/mercado pago integration.png" alt="" width="563"><figcaption></figcaption></figure>

Your Mercado Pago integration is now active.

{% hint style="info" %}
Test it by making a real purchase on your site.
{% endhint %}



To get started with products and services in your shop, see the following articles:

{% content-ref url="../shop/start.md" %}
[start.md](../shop/start.md)
{% endcontent-ref %}
