# Load balancing / SSL

```bash
# Create a self-signed certificate

openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout nginx-selfsigned.key -out nginx-selfsigned.crt
```