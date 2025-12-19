---
description: Connecting the Liqpay payment system
---

# LiqPay connection

[**LiqPay**](https://www.liqpay.ua/en) is a payment system for residents of Ukraine.

### How to connect Liqpay

* Sign up on [**Liqpay**](https://www.liqpay.ua/en).
* After registration, go to the **Company Activation** section and fill in the required details. Start by confirming your email.
* In the **Company information** section, provide links to your website and [Terms of Service](../legal/user-agreement.md). All links start with `https://`.

<figure><img src="../.gitbook/assets/liqpay activate company.png" alt=""><figcaption></figcaption></figure>

* In the **Details for receiving funds**, enter your **IBAN account**, **EGRPOU**, and **company name**.
* Select a **product category** and add a brief description of your business.

<figure><img src="../.gitbook/assets/liqpay iban business.png" alt="" width="506"><figcaption></figcaption></figure>

* **Upload the necessary documents** and submit your application for activation.

<figure><img src="../.gitbook/assets/liqpay apply.png" alt=""><figcaption></figcaption></figure>

* Once activated, go to **Settings → API**.

<figure><img src="../.gitbook/assets/liqpay settings api.png" alt=""><figcaption></figcaption></figure>

* In the **Server-to-Server Notification URL** field, enter the following address:

```
https://wfolio.com/gateway/integrations/liqpay/notify
```

* Copy your **public** and **secret** keys. Click on the **eye icon** to reveal the secret key.

<figure><img src="../.gitbook/assets/liqpay api keys.png" alt="" width="281"><figcaption></figcaption></figure>

* Go to Wfolio control panel. Navigate to the **Shop → Store settings**. Make sure that your currency is **hryvnia (UAH)**. Select Liqpay.
* Paste the **public and private (hidden) keys** into the fields. Click **Add** to complete the setup.

<figure><img src="../.gitbook/assets/liqpay integrate en.png" alt="" width="563"><figcaption></figcaption></figure>
