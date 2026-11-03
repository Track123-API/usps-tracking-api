# USPS Tracking API & Webhooks

Use Track123 to track USPS shipments through one unified shipment tracking API.

Track123 lets your application register USPS tracking numbers, retrieve tracking updates, and receive delivery events through webhooks.

- USPS carrier code: `usps`

- [Track USPS packages on Track123](https://www.track123.com/carriers/usps)

- [USPS API integration page](https://www.track123.com/carriers/usps/api)

- [Track123 API documentation](https://docs.track123.com)

> This repository explains how to track USPS shipments with Track123. It is not official USPS API documentation.

## USPS tracking API integration

When your application already knows that a shipment is handled by USPS, set `courierCode` to `usps` when registering the tracking number.

Use [Carrier Detection](https://docs.track123.com/reference/detection-courier) when your application does not have an approved carrier code.

Use your own tracking number in the registration request. Track123 does not provide public test tracking numbers in this repository.

## Integration guides

- [USPS tracking webhook](webhook.md)
- [USPS tracking statuses](tracking-status.md)
- [USPS API errors and rate limits](errors-and-rate-limits.md)

## USPS tracking API resources

- [Register package trackings](https://docs.track123.com/reference/register-package-trackings)
- [Get package trackings](https://docs.track123.com/reference/get-package-trackings)
- [Carrier detection](https://docs.track123.com/reference/detection-courier)

## Track USPS packages and view FAQs

For shipment lookup, carrier contact information, and customer-facing FAQs, visit [USPS tracking on Track123](https://www.track123.com/carriers/usps).

## More Track123 resources

- [All supported carriers](https://www.track123.com/carriers)
- [Track123 developer documentation](https://docs.track123.com)

Carrier names and websites are used only to identify compatible carriers. Track123 is not affiliated with or endorsed by USPS unless explicitly stated.
