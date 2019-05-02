# Frequently Asked Questions

- [Why is the service I want to use grayed out?](#why-is-the-service-i-want-to-use-grayed-out)
- [How do I generate a certificate for my integration?](#how-do-i-generate-a-certificate-for-my-integration)

### Why is the service I want to use grayed out?

In order to create an integration on I/O Console: 

1. You must be part of an Enterprise Organization.
2. You must be a System Administrator within that Organization.
3. Your organization must be provisioned to use that particular service. Contact your Enterprise account representative to get your organization provisioned for additional services.

### How do I generate a certificate for my integration?

Using the openssl command line utility:

```
openssl req -x509 -sha256 -nodes -days 365 -newkey rsa:2048 -keyout private.key -out test.crt
```
