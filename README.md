# Acme Markets (acme-markets)

Acme Markets is a regional supermarket chain founded in 1891 and headquartered in the U.S. Northeast, operating approximately 164 stores across Pennsylvania, New Jersey, Delaware, New York, Connecticut, and Maryland. Acme is a banner of Albertsons Companies, Inc., one of the largest food and drug retailers in the United States. The brand has no publicly documented developer program or public API: digital surfaces (store locator, loyalty program "ACME for U", FreshPass subscription, DriveUp & Go, delivery, pharmacy) are delivered through Albertsons-shared web and mobile platforms. The Android package ID (`com.safeway.client.android.acme`) confirms that the Acme app is built on the shared Safeway/Albertsons banner application, suggesting a shared backend API surface across Albertsons banners that is not externally published.

**URL:** [Visit APIs.json URL](https://www.acmemarkets.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Albertsons Banner, Delivery, E-Commerce, Grocery, Loyalty, Pharmacy, Retail, Store Locator, Supermarket

## Timestamps

- **Created:** 2026-05-22
- **Modified:** 2026-05-23

## APIs

### Acme Markets Store Locator

Public store-locator surface used by the Acme Markets website to render store information (address, hours, services, phone, departments). Pages are rendered under the `local.acmemarkets.com` subdomain, a pattern typical of vendor-hosted local-pages SEO platforms (e.g. Rio SEO, Yext, Brandify). No public JSON endpoint or developer documentation has been published; the locator UI is the only externally observable surface.

**Human URL:** [https://local.acmemarkets.com/search.html](https://local.acmemarkets.com/search.html)

#### Tags:

 - Locations, SEO, Store Locator

#### Properties

- [Documentation](https://local.acmemarkets.com/search.html)

### ACME for U Loyalty Program

ACME for U is the chain's free loyalty program, surfacing personalized weekly ad deals, digital coupons, and Points redeemable for fuel and groceries. The program is delivered through the Acme Markets website and mobile app and shares the underlying account and offers platform with other Albertsons banners (Safeway, Vons, Jewel-Osco, etc.). No public OAuth/API documentation is available; integrations are performed exclusively through the first-party web and mobile clients.

**Human URL:** [https://www.acmemarkets.com/foru/program-details.html](https://www.acmemarkets.com/foru/program-details.html)

#### Tags:

 - Coupons, Deals, Loyalty, Points, Rewards

#### Properties

- [Documentation](https://www.acmemarkets.com/foru/program-details.html)
- [SignUp](https://www.acmemarkets.com/account/register.html)

### FreshPass Delivery Subscription

FreshPass is the Albertsons-family paid subscription that provides unlimited free grocery delivery, exclusive deals, and additional Points on the Acme Markets e-commerce platform. The Acme storefront markets FreshPass directly; the subscription management surface is shared across Albertsons banners. There is no publicly documented API.

**Human URL:** [https://www.acmemarkets.com/freshpass.html](https://www.acmemarkets.com/freshpass.html)

#### Tags:

 - Delivery, Membership, Subscription

#### Properties

- [Documentation](https://www.acmemarkets.com/freshpass.html)

### DriveUp & Go Curbside Pickup

DriveUp & Go is the Acme Markets / Albertsons-family curbside pickup product ordered through the website and mobile app. Customers build an order online, schedule a pickup window, and check in via the app. The ordering, slot, payment, and fulfillment endpoints are not exposed as a public developer API.

**Human URL:** [https://www.acmemarkets.com/grocery-delivery-services.html](https://www.acmemarkets.com/grocery-delivery-services.html)

#### Tags:

 - Curbside, E-Commerce, Fulfillment, Pickup

#### Properties

- [Documentation](https://www.acmemarkets.com/grocery-delivery-services.html)

### Acme Markets Pharmacy

Acme Markets operates in-store pharmacies offering prescription refills, transfers, immunizations, and pharmacy account management. The pharmacy surface is delivered through the website and the shared Albertsons mobile app. No public API is documented; HIPAA-regulated workflows operate over first-party authenticated channels only.

**Human URL:** [https://www.acmemarkets.com/pharmacy.html](https://www.acmemarkets.com/pharmacy.html)

#### Tags:

 - Healthcare, Pharmacy, Prescriptions, Vaccines

#### Properties

- [Documentation](https://www.acmemarkets.com/pharmacy.html)


#### Tags:

 - Android, Mobile App, iOS

#### Properties

- [Documentation](https://www.acmemarkets.com/about-us/mobile-apps.html)
- [iOSApp](https://apps.apple.com/us/app/acme-markets-deals-rewards/id667621570)
- [AndroidApp](https://play.google.com/store/apps/details?id=com.safeway.client.android.acme)

## Common Properties

- [Website](https://www.acmemarkets.com)
- [AboutUs](https://www.acmemarkets.com/about-us.html)
- [ParentCompany](https://www.albertsonscompanies.com)
- [Careers](https://www.acmemarkets.com/about-us/careers.html)
- [ContactUs](https://www.acmemarkets.com/about-us/contact-us.html)
- [TermsOfService](https://www.acmemarkets.com/content/dam/shared/legal/terms-of-use.html)
- [PrivacyPolicy](https://www.acmemarkets.com/content/dam/shared/legal/privacy-policy.html)
- [GitHubOrganization](https://github.com/api-evangelist/acme-markets)

## Features

| Name | Description |
|------|-------------|
| ACME for U Loyalty | Free loyalty program with personalized deals, digital coupons, and Points redeemable for fuel and groceries. |
| FreshPass Subscription | Paid membership providing unlimited free grocery delivery and exclusive member pricing on the Acme e-commerce platform. |
| DriveUp & Go Curbside Pickup | Schedule-based curbside grocery pickup ordered through the website or mobile app. |
| Home Delivery | Grocery home delivery across the Northeast service area through the Acme storefront. |
| In-Store Pharmacy | Pharmacy services including prescription refills, transfers, immunizations, and account management. |
| Fuel Rewards | Points earned through ACME for U can be redeemed for cents-off per gallon at participating fuel stations. |
| Store Mode | In-store mobile app mode surfacing aisle locations and one-tap coupon clipping while shopping. |
| Mobile Application | Native iOS and Android client built on the shared Safeway/Albertsons banner codebase consolidating all shopping surfaces. |

## Use Cases

| Name | Description |
|------|-------------|
| Store Discovery | Locate the nearest Acme Markets store, departments, hours, and pharmacy services via the store locator. |
| Weekly Ad Shopping | Browse the personalized weekly ad, clip digital coupons, and build a shopping list before visiting the store. |
| Online Grocery Ordering | Place orders for DriveUp & Go pickup or home delivery through the website or mobile application. |
| Pharmacy Management | Refill prescriptions, transfer pharmacies, and schedule immunizations through the digital pharmacy surface. |
| Loyalty Engagement | Earn and redeem Points across grocery and fuel purchases through the ACME for U program. |

## Integrations

| Name | Description |
|------|-------------|
| Albertsons Companies Platform | Acme is operated as an Albertsons banner; loyalty, e-commerce, pharmacy, and mobile surfaces share the parent platform. |
| Safeway Mobile Codebase | The Acme Markets mobile app is built on the shared Safeway / Albertsons banner application (Android package `com.safeway.client.android.acme`). |
| FreshPass Membership | Cross-banner Albertsons subscription product surfaced on the Acme storefront. |
| Local Pages Platform | Per-store landing pages delivered via the `local.acmemarkets.com` subdomain, a pattern typical of vendor-hosted local-pages SEO platforms. |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
