# How to connect a domain purchased elsewhere

To connect a domain registered with another registrar to your Wfolio website or drive, follow these steps:

* Go to the **Site Address** (or **Disk Web Address**) settings section.
* Click on the **I already have a domain** link.
* In the window that opens, enter your domain and click **Connect**.
* Configure the domain at your registrar.

<figure><img src="../.gitbook/assets/i already have a domain en.png" alt="" width="563"><figcaption></figcaption></figure>



### How to switch domains if you already have one connected

* <mark style="color:blue;">**Change domain**</mark> button. If you've registered a domain through Wfolio, you will see a **Change Domain** button. Click on it and connect any free `.wfolio.pro` domain first.
* <mark style="color:red;">**Disable domain**</mark> button. If you previously connected a domain from another registrar, click **Disable Domain** to disconnect it.

After this is done, click on the **I already have a domain** link and connect your domain.

Then configure the domain at your registrar.

***



## Configuring domain at your registrar

This can be done in two ways.

### Specify Wfolio servers as DNS servers

This method is best if you don't need to add custom domain records (e.g., A, AAAA, MX, TXT) for connecting a subdomain or a mail service.

* Update the DNS settings for your domain to point to Wfolio's DNS servers.
* **Ensure that only two DNS servers remain in your settings**.

| NS server | Value               |
| --------- | ------------------- |
| NS1       | **dns1.wfolio.com** |
| NS2       | **dns2.wfolio.com** |

{% hint style="warning" %}
After updating the DNS servers, it may take up to 48 hours for changes to propagate. Your site will be accessible with the new domain once the DNS update is complete.
{% endhint %}



### Add (or edit) A records in the DNS editor

This method is useful if:

* Your registrar doesn't allow changing DNS servers.
* You have email services connected or plan to connect an email service.
* You want to create subdomains or add additional records (e.g., A, AAAA, MX, TXT).

Add or edit two records:

1. In the field **Name** or **Host** pass the `@` symbol. Some registrars require you to specify your domain name instead of the `@` symbol, e.g., `example.com`. If neither option works, leave this field blank.
2. In the field **Name** or **Host** enter `www` and specify value and TTL listed below.

* **Make sure that the domain has only two A records with the names `@` and `www`.** If there are additional records for these hosts, it may cause an IP address conflict and lead to connection errors.
* If the domain has AAAA records for `@` or `www`, they must be deleted.

### European (worldwide) servers

| Type | Name (Host)  | Value               | TTL  |
| ---- | ------------ | ------------------- | ---- |
| А    | **@**        | **103.137.248.164** | 3600 |
| А    | **www**      | **103.137.248.164** | 3600 |

### USA servers

| Type | Name (Host)  | Value             | TTL  |
| ---- | ------------ | ----------------- | ---- |
| А    | **@**        | **45.83.140.234** | 3600 |
| А    | **www**      | **45.83.140.234** | 3600 |

To make your website function on servers in Kazakhstan or in Belarus, add the following domain records.

### Kazakhstan servers

| Type | Name (Host) | Value            | TTL  |
| ---- | ----------- | ---------------- | ---- |
| A    | @           | **213.148.2.60** | 3600 |
| A    | www         | **213.148.2.60** | 3600 |

### Belarus servers

| Type | Name (Host) | Value             | TTL  |
| ---- | ----------- | ----------------- | ---- |
| A    | @           | **45.135.234.71** | 3600 |
| A    | www         | **45.135.234.71** | 3600 |

***

### Configure a domain with Wix

If your domain is hosted on Wix, follow these steps to configure it:

* Go to the DNS record settings.
* In the **A (Host)** block, change the **Address** field to the value `159.69.249.27` instead of the existing IP address.
* In the **CNAME (Aliases)** block, enter your domain name without `www` (e.g., `mydomain.com`) in the **Address** field.
* Delete any other aliases listed in the **CNAME** block.

| Host Name           | Points to           | TTL     |
| ------------------- | ------------------- | ------- |
| `mydomain.com`      | **103.137.248.164** | 1 Hour  |
| **CNAME (Aliases)** | **Points to**       | **TTL** |
| `www.mydomain.com`  | `mydomain.com`      |  Hour   |

***

If you have any problems with connecting a domain—leave a message to our support team. We will be happy to help you.
