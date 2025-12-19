---
description: How to connect a subdomain to the website or galleries
---

# Сonnecting a subdomain

If you have a registered domain, such as `mydomain.com`, you can connect a subdomain like `gallery.mydomain.com` to your Wfolio website or galleries. Each Wfolio account can have only **one** domain or subdomain connected at a time.

{% hint style="info" %}
If you registered your domain [**through Wfolio**](new.md) or connected it via [**Wfolio DNS servers**](existing-domain.md#specify-wfolio-servers-as-dns-servers), you’ll need to contact support via live chat to enable subdomain setup.
{% endhint %}

* Go to **Settings → Site Address** or **Disk Web Address**. Click on the **I already have a domain** link.

<figure><img src="../.gitbook/assets/i already have a domain en.png" alt="" width="563"><figcaption></figcaption></figure>

* Enter your subdomain (e.g., `gallery.mydomain.com`).
* Click on the **Connect** button.

Then you see the **settings** you need to **enter on your domain registrar's website**.



### Configure the subdomain in your registrar's panel

Add **two A records** pointing to Wfolio's IP address:

1. Set the first record's **host name** as your subdomain (e.g., `gallery`).
2. Set the second record's **host name** as `www.gallery`.

{% hint style="info" %}
Some domain registrars may require you to **create the subdomain first** before adding A records.
{% endhint %}

Choose the appropriate **server location** based on your needs.



#### Worldwide servers

| Type | Name (Host) \* | Value               | TTL  |
| ---- | -------------- | ------------------- | ---- |
| A    | gallery        | **103.137.248.164** | 3600 |
| A    | www.gallery    | **103.137.248.164** | 3600 |

#### Kazakhstan servers

|   |             |                  |      |
| - | ----------- | ---------------- | ---- |
| A | gallery     | **213.148.2.60** | 3600 |
| A | www.gallery | **213.148.2.60** | 3600 |

#### Belarus servers

| Type | Name (Host) | Value             | TTL  |
| ---- | ----------- | ----------------- | ---- |
| A    | gallery     | **45.135.234.71** | 3600 |
| A    | www.gallery | **45.135.234.71** | 3600 |

***

### Configure a domain with Wix

{% hint style="info" %}
After entering the settings, the subdomain should connect **within two days**.
{% endhint %}

If there are any problems during the connection process, write to us in the support chat on the website.
