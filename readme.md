# About this Project

### The Third-Party JS File Used

[https://github.com/dankogai/js-base64](https://github.com/dankogai/js-base64)

### The Encryption Algorithms Used

- ECDH
- AES-GCM

### Disclaimer

This project does not guarantee security.

Taking convenience into account, the project has significantly reduced the length of the encryption key, verification tag, and random IV.

Meanwhile, the P-256 curve has also been questioned for potential backdoors.

Therefore, please refrain from using this project in situations where strict confidentiality is required.

# Guide

When you first use this website, a basic user manual will pop up.

Generally, all you need to do is follow these instructions.

### Warning

Typically, local-storage API which is used by this project to store chat data can only contain around 5-10MB of data.

Exceeding this limit may result in the webpage crashing.

Please remember to promptly delete any unnecessary conversations.
