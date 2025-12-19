---
description: Selling photos online with Wfolio Galleries
---

# How to sell digital photos

### How it works

* You can enable photo selling mode for any project.
* Once the photos are uploaded, a watermark is automatically applied to them.
* The client adds photos to their cart. An email is sent with a link to the cart, so they can return to it later.
* After completing payment online, the client can download the photos without a watermark. There are two ways to do this:
  * Download directly from the cart after payment.
  * Follow the link in the confirmation email—this is sent automatically after payment is completed.

{% hint style="success" %}
To start selling photos, connect a [payment system](../online-payments/payment-systems.md).
{% endhint %}

#### Gallery example with photo selling feature

<a href="https://gallery.wfolio.pro/disk/wonderful_nature" class="button secondary" data-icon="images">Shop description, discount for 10+ photos</a>

### How to enable photo selling

* Connect a [payment system](../online-payments/payment-systems.md).
* In the main project settings, select **Photo selling** as the project type.

<figure><img src="../../.gitbook/assets/photo selling set up en.png" alt="" width="563"><figcaption></figcaption></figure>

* Set the price per photo. To set a discount, click on the add discount button under the price for a photo.

<figure><img src="../../.gitbook/assets/set up discount photo selling en.png" alt="" width="563"><figcaption></figcaption></figure>

* You can also set up to three discount tiers (in percentages), depending on how many photos are selected in the cart:

<figure><img src="../../.gitbook/assets/photo selling discounts en.png" alt="" width="563"><figcaption></figcaption></figure>

{% hint style="info" %}
#### Test purchase

Remember to test the process to ensure everything is working correctly.

Once payment is complete, the photo order should appear in the **Store** section.

> If the order doesn’t show up in **Orders** or is stuck in **Unfinished** after several hours, check your payment system’s HTTP notification settings.
{% endhint %}

#### Carts section

In a photo selling project, you’ll see a **Carts** section, which shows the photos selected by each client.\
This includes both completed and in-progress orders.

<figure><img src="../../.gitbook/assets/photo selling carts en.png" alt=""><figcaption></figcaption></figure>

#### Client name in the order form

Clients are always prompted to enter their **name**—this helps identify the cart.\
Go to the **Drive settings** to choose how the name request appears during photo purchases and [favorites selections](../../gallery/selections/make-favorites-list.md).

This is useful if you want to request just a **First name** or ask for **Last name, First name** in a strict order.

<figure><img src="../../.gitbook/assets/client name drive en.png" alt="" width="563"><figcaption></figcaption></figure>

### Frequently Asked Questions

* **My customer paid for the photos but the photos were not offered for download, and no email with a link was received. What went wrong?**\
  Make sure that HTTP notifications are configured correctly in your payment system. If they are not set up, Wfolio will not receive a notification of the successful payment from a payment system. Detailed settings can be found in the instructions for each payment system: [stripe.md](../../payments/stripe.md "mention"), [liqpay.md](../../payments/liqpay.md "mention").
*   **Can I set different prices for photos?**\
    Within one project, the price is the same for all photos, but you can set discounts depending of the amount of photos to be purchased.

    You can set different prices for each separate project.
* **Can I set different download sizes for photos?**\
  Photos can be downloaded in their original size and in a resized version for social media, if such version is enabled in the **Settings → Drive Settings** section.
* **Will the customer gain access to download the photos?**\
  Yes. After a successful payment, customers can download the photos without watermarks via an email link or directly from the cart.
* **How long will the photos be available for download?**\
  The download link will be valid until the project is deleted from the drive.
* **How can I have both a favorites list and a cart at the same time?**\
  This is not possible. You can create two separate projects, or first use the favorites list feature, and then change the project type to photo selling.
* **Can I use this feature to sell printed photos?**\
  Photo sales are available in **digital form**, so for selling printed products, we recommend using the [Shop section](/broken/pages/uOz0hHseeJ09OQr4SMVx). See the article: [products.md](products.md "mention").
