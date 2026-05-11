# RetailorID - Retailor Media GTM Template

The official Google Tag Manager template for installing the **RetailorID** tracking script on your website.

---

## Requirements

- A Google Tag Manager **web container**
- A **Provider ID** provided by Retailor Media (UUID format)
- A Consent Management Platform (CMP) — recommended for GDPR compliance

---

## Installation

1. Download `template.tpl` from this repository
2. In GTM, go to **Templates** > **Tag Templates** > **New**
3. Click the menu icon (⋮) > **Import**
4. Select the downloaded `template.tpl` file
5. Click **Save**

The template **RetailorID - Retailor Media** is now available in your tag library.

---

## Basic Setup

1. Create a new tag: **Tags** > **New** > select **RetailorID - Retailor Media**
2. Enter your **Provider ID** (provided by Retailor Media)
3. Set **Event Name** to `Standard` > `pageview`
4. Add a firing trigger based on user consent:
   - If your CMP supports **TCF2**: use vendor consent for **Retailor Media S.R.L (IAB code 1532)**
   - Otherwise: fire the tag only when consent for profiling cookies is granted
5. Save and publish

---

## Documentation

Full implementation guide (e-commerce events, customer data, custom variables, GA4 integration):

[docs/RetailorMedia-TagManager-Template.md](docs/RetailorMedia-TagManager-Template.md)

---

## Support

For Provider ID requests or technical support, contact [Retailor Media](https://www.retailor.media/).
