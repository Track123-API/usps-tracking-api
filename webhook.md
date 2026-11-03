# USPS Tracking Webhook with Track123

Receive USPS shipment tracking updates in your application through Track123 webhooks.

> This guide uses Track123's unified webhook flow. It is not official USPS webhook documentation.

## Set up USPS tracking updates

1. Register the shipment with Track123.

2. Set `courierCode` to `usps` when USPS is already known.

2. Use [Carrier Detection](https://docs.track123.com/reference/detection-courier) when the carrier code is not available.

3. Add an HTTPS webhook URL in Track123.
4. Select the tracking events your application needs.
5. Verify the webhook signature before processing the event.
6. Handle repeated deliveries safely with idempotent processing.

## Webhook security and retries

Validate every received event according to the Track123 webhook guide. Keep your webhook endpoint private, log delivery failures safely, and return a successful response only after your application accepts the event.

## Resources

- [Track123 webhook guide](https://docs.track123.com/reference/getting-started-with-your-api)
- [Track123 delivery status reference](https://docs.track123.com/reference/package-status)
- [Track USPS packages on Track123](https://www.track123.com/carriers/usps)
- [Back to USPS tracking API](README.md)
