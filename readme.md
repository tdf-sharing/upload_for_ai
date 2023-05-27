# About

### _The Third-Party JS File Used_

- [js-base64](https://github.com/dankogai/js-base64)

### _The Encryption Algorithms Used_

- ECDH
- AES-GCM

### _Disclaimer_

__Security is not guaranteed__

- Taking convenience into account, the project has significantly reduced the length of the encryption key, verification tag, and random IV

- The P-256 curve has been questioned for potential backdoors

# Guide

When you first use this website, a basic user manual will pop up.

Generally, all you need to do is follow these instructions.

### _Warning_

Typically, local-storage API which is used by this project to store chat data can only contain around 5-10MB of data.

Exceeding this limit may result in the webpage crashing.

Please remember to promptly delete any unnecessary conversations.
