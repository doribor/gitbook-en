---
description: >-
  When clicking on a phone number, the user will be offered to make a call to
  the specified number
hidden: true
noIndex: true
---

# How to make a phone number clickable

To make the phone number clickable, you need to add a link in the format:

```elixir
tel:+PhoneNumber
```

{% hint style="warning" %}
The phone number must be specified in the international format starting with the `+` symbol, without brackets, spaces and dashes. For example, **tel:+46701234567**.
{% endhint %}

The clickable phone number can be made in the text, by the button or in the main menu of the site. How to make each of the options step by step.

## Clickable phone in the text

When editing a page, **highlight a phone number** or any other piece of the text, then in the text formatting panel above it click on the link icon and add a link to the phone in the format **tel:+PhoneNumber**.

## A button with a clickable link

Go to the button settings. Select the **action Make a phone call** and enter your phone number with the country code.

<figure><img src="../../.gitbook/assets/make a phone call button.png" alt="" width="563"><figcaption></figcaption></figure>



### Clickable phone number in the menu

Click the **Add to the site** button and select the **Link** item. In the window that opens, enter the name of the link and enable the **Display in the site menu** option. Choose the action **Make a phone call** and enter your phone number with the country code.

<figure><img src="../../.gitbook/assets/phone menu link.png" alt="" width="563"><figcaption></figcaption></figure>

## Link to WhatsApp

The same way you can make a clickable link to WhatsApp. In order to do this, use the format:

```elixir
https://wa.me/PhoneNumber
```

{% hint style="warning" %}
The phone number must be specified without the `+` symbol. For example, **https://wa.me/46701234567**.
{% endhint %}
