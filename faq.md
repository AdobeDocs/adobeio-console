# Frequently Asked Questions

This document provides answers to frequently asked questions about Adobe Developer Console. This is a great place to start when troubleshooting a problem with Console. If you are unable to find the answer you're looking for, please refer to the [Support overview](support.md) for additional resources.

## Questions

- [Why is the service I want to use grayed out?](#why-is-the-service-i-want-to-use-grayed-out)
- [How do I generate a certificate for my integration?](#how-do-i-generate-a-certificate-for-my-integration)


## Answers

### Why is the service I want to use grayed out?

To create an integration on I/O Console: 

1. You must be part of an Enterprise Organization.
2. You must be a System Administrator within that Organization.
3. Your organization must be provisioned to use that particular service. Contact your Enterprise account representative to get your organization provisioned for additional services.

### How do I generate a certificate for my integration?

Using the openssl command line utility:

```
openssl req -x509 -sha256 -nodes -days 365 -newkey rsa:2048 -keyout private.key -out certificate_pub.crt
```
